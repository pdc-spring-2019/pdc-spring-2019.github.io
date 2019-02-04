# Homework Assignment Instructions

This homework assignment is designed to mimic the html assignment in that you will add Cascading Stylesheets (CSS) rules to your Github Pages site to demonstrate an introductory level familiarity/competence with the idea of styling your web pages with rules. As I suggested in class, the crucial skills at this stage are CSS syntax, CSS selectors, and several often-used CSS styling rules. 

### Add rules to a stylesheet

(See https://www.w3schools.com/css/css_syntax.asp for a refresher on syntax)

1. On your Github Pages site, create a folder called ```css``` and a file in that folder called ```style.css```
2. In your ```style.css``` document, add a rule that gives all ```<hr>``` elements a bottom margin of 35 pixels and a top margin of 25 pixels. 
3. In your ```style.css``` document, add a rule that makes all ```<li>``` text blue
4. In your ```style.css``` document, add a rule that makes all ```<code>``` tag text have a font of Helvetica with all text underlined 
5. In your ```style.css``` document, add a rule that makes any element with a class equal to "caption" have a width of 50% and appear in italic. Then add ```<div class="caption">Some caption text</div> ``` to your ```index.html``` file
6. In your ```style.css``` document, add a rule that makes any element with an id equal to "most_important" have a light gray background, a width of 200 pixels, and a height of 100 pixels. Then add ```<div id="most_important">Some important text</div> ``` to your ```index.html``` file
7. Connect your ```index.html``` file to the rules you have created by adding a ```<link>``` tag inside your ```index.html``` file's ```<head></head>``` element. Note that you should use a relative path to the ```style.css``` file when entering a value for the ```rel``` attribute. 
8. Wait about five minutes and verify that your changes appear on your Github Pages site

### Add the bootstrap4 files to your Github Pages repository

1. Download the bootstrap4 library from https://getbootstrap.com/docs/4.0/getting-started/download/
2. Unzip the files
3. Upload the contents of the CSS folder to the folder on your Github Pages site called CSS. Do not delete your ```style.css`` file from Part I of this homework.
4. Upload the JS folder to your Github Pages site 
5. Connect your ```index.html``` file to the ```bootstrap.min.css``` file by adding a ```<link>``` tag inside your ```index.html``` file's ```<head></head>``` element, just above your ```<link>``` tag for the ```style.css``` file. 
As with the ```style.css``` file, you should use a relative path to the bootstrap file when entering a value for the ```rel``` attribute. 

Note: adding the bootstrap library to your ```index.html``` file may make some of your ```style.css``` styles disappear, but that's no problem. I'll still be able to see the work you did. 

### Trying some bootstrap rules

1. Add the following code to your ```index.html``` file (copy and paste is allowed):

```
<div class="alert alert-primary" role="alert">
  A simple primary alert—check it out!
</div>
```

2. Add the following code to your ```index.html``` file (copy and paste is allowed):

```
<div class="list-group">
  <a href="#" class="list-group-item list-group-item-action">Dapibus ac facilisis in</a>

  
  <a href="#" class="list-group-item list-group-item-action list-group-item-primary">A simple primary list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-secondary">A simple secondary list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-success">A simple success list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-danger">A simple danger list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-warning">A simple warning list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-info">A simple info list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-light">A simple light list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-dark">A simple dark list group item</a>
</div>
```

3. Add the following code to your ```index.html``` file (copy and paste is allowed):

```
<p>
  <a class="btn btn-primary" data-toggle="collapse" href="#multiCollapseExample1" role="button" aria-expanded="false" aria-controls="multiCollapseExample1">Toggle first element</a>
  <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#multiCollapseExample2" aria-expanded="false" aria-controls="multiCollapseExample2">Toggle second element</button>
  <button class="btn btn-primary" type="button" data-toggle="collapse" data-target=".multi-collapse" aria-expanded="false" aria-controls="multiCollapseExample1 multiCollapseExample2">Toggle both elements</button>
</p>
<div class="row">
  <div class="col">
    <div class="collapse multi-collapse" id="multiCollapseExample1">
      <div class="card card-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
      </div>
    </div>
  </div>
  <div class="col">
    <div class="collapse multi-collapse" id="multiCollapseExample2">
      <div class="card card-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
      </div>
    </div>
  </div>
</div>
```


