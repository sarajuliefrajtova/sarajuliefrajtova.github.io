# TYPOGRAPHY CSS LIBRARY #
**Author:** *Sara Julie Frajtova*
## Demo site
Link to **[demo](http://sarajuliefrajtova.github.io/typography/)** site for preview.
## Dependecies
``` 
<link rel="stylesheet" href="./style/normalize.css">
``` 
## Implementation
``` 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style/style.css">
    <link rel="stylesheet" href="./style/typhography.css">
    <link rel="stylesheet" href="./style/queries.css">
    <link rel="stylesheet" href="./style/normalize.css">
    <title>CCS typografická knihovna</title>
</head>
``` 
## Usage
This library is recommended for a blog posts pages use. CSS files are primarly based on styling HMTL tags such as ```<section>```,  ```<h1>, <h2>``` etc.:
- ol/ul, li
- blockquote
- p, a
- h1 (**not** part of an section), h2, h3, h4, h5, h6


There are also some components which can be initialized by classes - e.g. ``` .wrapper ```. To ``` .wrapper ``` class is assigneted a certain **max-width** that gives "natural" margin to whole page. The ``` .wrapper ``` should be applied on ``` <div> ``` tag, with the following structure: 

``` 
<main>
        <div class="wrapper">
            <h1>1st heading</h1>
            <ul class="post-info">
                <li> Author: <span>Lorem ipsum</span></li>
                <li>Date: <span>DD. MM. YYYY</span></li>
            </ul>
            <figure>
                <img src="https://via.placeholder.com/1000x500" alt="img" class="welcome-img">
                <figcaption>Lorem ipsum dolor sit amet consectetur adipisicing elit.</figcaption>
            </figure>
            <section>
                <h2>2nd heading</h2>
                .
                .
                .
            </section>
         </div>
</main>
```

## Components

### Header 
If you want, you can even use the ```<header> ``` section with the following ```.nav-bar``` class. 
``` 
 <header>
        <nav class="nav-bar">
            <ul>
                <li><a href="#">Logo</a></li>
                <li><a href="#">2nd item</a></li>
                <li><a href="#">3rd item</a></li>
            </ul>
        </nav>
    </header>
``` 

### 
### Second
