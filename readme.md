# Advanced CSS Practice

### There are three pillars to write good HTML and CSS
- Responsive design
 * Fluid Layouts
 * Media Queries
 * Responsive images
 * Correct units
 * Desktop-first vs mobile-first

- Maintainable and Scalable code
  * Clean
  * Easy-to-understand
  * Growth
  * Reusable for other developers
  * How to organize files (need to think about css architecture)
  * How to name classes
  * How we structure or markup in HTML

- Web Performance
  * Making an app more performant means to make it faster and smaller in size so that user has to download less data
  * Less HTTP requests
  * Less code
  * Compress code
  * Use a css preprocessor
  * Less images
  * Compress images

### What Happens to CSS when we load a Webpage

When the browser loads a HTML file, it then takes then loaded html code and parses it which means it decodes it line by line. From this process, the browser builds DOM which describes the entire web document like a family tree with parents and children and sibling elements. This DOM is where the entire decoded HTMl code is stored.

When the browser parses html, it also finds the stylesheets included in the html head and starts loading them and hence css is parsed.

The parsing of CSS is a bit complex. Follows two main steps:

1. Resolving Confilicting CSS Declarations (cascade)
- cascade is the process that is used to resolve conflict
2. Process final CSS values
- Like converting margin unit from percentage to pixels

The final CSS is also stored in a tree-like structure known as CSS Object Model (CSSOM) like DOM. In order to have html and css parsed ans stored. In order to render page, the browser uses the **visual formatiing model** like box-model (floats, positioning).

Finally, the visual formatting model has done its work, the website is finally rendered.