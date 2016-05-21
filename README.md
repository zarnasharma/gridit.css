#gridit.css
*A simple CSS grid layout*

`gridit.css` is a simple CSS grid layout based on Flexbox and Responsive Grid System that works wonder with simple web pages and can be modified to do awesome things with complex ones too

##Usage
1. After downloading and extracting the css file, simply add it to the `head` of your file.

  ```html
  <head>
    <link rel="stylesheet" href="gridit.css"/>
  </head>
  ```
2. Example

[Full Example here](http://zarnasharma.github.io/gridit.css/)
```html
  <body>
   <div class="row">
    <div class="col-6">
     <!--column spanning 50% of total body width -->
    </div>
    <div class="col-6">
     <!--column spanning 50% of total body width -->
    </div>
   </div>
   <div class="row">
    <div class="col-4">
     <div class="row">
      <div class="col-6">
       <!--column spanning 50% of 33.33% body width -->
      </div>
      <div class="col-6">
       <!--column spanning 50% of 33.33% body width -->
      </div>
     </div>
    </div>
    <div class="col-8">
     <!--column spanning 66.66% of total body width -->
    </div>
   </div>
  </body>
  ```
## License
gridit.css is licensed under the MIT license. (http://opensource.org/licenses/MIT)

