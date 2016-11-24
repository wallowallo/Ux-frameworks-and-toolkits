# UX Frameworks History and details

## UX Frameworks and Toolkits

### Dojo toolkit 

- Appeared around 2002-2003. And it provided a set of widgets built in javascript which were meant to be dynamic.

### EXTJS 

- Appeared around 2007. The company that makes it is now named sencha. Provided a set of widgets as well as various tools to easily manipulate html and JS.
- After EXTJS the communmity understood the power of js frameworks and focused js frameworks like backbone, meteor and angularJS appeared. These new js frameworks were focused on the js only to create complex js applications. And did not focus on the styling of widgets or even the widgets themselves. Instead they facilitated, creating these widgets in another higher level frameworks. 

### Bootstrap

- Bootstrap was built by twitter to provide a lot of css predefined classes. And also some more complex widgets which required js and were built using jQuery. Later on bootstrap got translated into other frameworks(not that jQuery is a framework). Other frameworks such as angularJS and react. Bootstrap also has a lot of skins available. 

### Foundation

- Foundation appeared maybe before bootstrap and is vary much loved by its users. However the community was steered towards somehow bootstrap more. Therefore foundation doesnt have the same level of community support(skins, plugins, commiters on github). Foundation also has several different implementations and different frameworks. 

### Google Material Design

- Google MT is not a css framework itself. Instead its a design specifiction with lots of cientifical studies behind it, gone as far as how aincient egypt was designing interfaces to communicate with. Google studied for a very long time, then produced a google MT specification document. which is available online. material.google.com/
- The most well known google material design based frameworks 
    - Material Design Lite getmdl.io/: Framework agnostic implementation.
    - Angular 1 Material implemented in angular 1, one of the more mature implementations contains a lot of js dynamic components.
    - Polymer Ux toolkit which you can import as web components(web components are a technology that allow you to import entire html apps in you html page).


### Basscss

- While a lot of people prefered using a js framework specific ux framework some considered the cupling with a specific framework an architectural limitation. BassCss is a css only ux framework which provides a very low level interface for developers to manipulate basic css properties through css classes. It basicly enables a js developer to follow style guide and apply predefined css classes without ever having to worry about writing css code for styling and positioning. Or writing specific css code for different browsers. 

### Tachyons

- Tachyons is a new css ux toolkit which seems to be like basscss framework agnostic and provide a low level interface to compose css classes, but unlike basscss it seems to offer higher level components as well. 

## Responsive grids

Some of the ux toolkits and frameworks provide responsive grid features. This means that you can define special classes for each type of screen size. Large medium small. generally a large screen is a laptop or computer. A medium screen is a tablet and a small screen is a smart phone. These responsive grids are built on top of css media queries. 

## Responsive designs

A responsive design is a design which the aplication styles are written in such a way that the application looks different on different screen sizes, but always looks good. 

## CSS pre-processors

Not to be confused with css toolkits. Css pre-processors are higher level css languages which are translated(transpiled/compiled) into css. A css pre-processor language is to css what typescript is to javascript. 
Common encountered css pre-processors:
    - Sass the most popular css pre-processor extends the css language by providing it with more programatic features such as variables and inheritance. Reducing the amount of css you need to write.
    - Less 
    - Stylus
    - Css next: Css next is to css what babelJS is to JS. Basicly a pre-processor language which implements the latest language specifications. And gets translated into regular css which can be interpreted by the browser. As an example currently css next provides the developer with css 4 features. While no browser supports css 4 yet. Many teams and organisations prefer to use sass while other teams have lately started to rely more on css toolkits such as tachyons and protect their js developers from having to deal with low level css preprocessed or not. 
