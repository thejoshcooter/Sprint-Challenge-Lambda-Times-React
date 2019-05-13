#Self-Study/Essay Questions

## What are PropTypes used for? Please describe why it's important to type check out data in Javascript.  
PropTypes are used to check the data type that we are passing down as state and props to ensure that we can throw early errors if data of the wrong type is passed. It's a test.  

## Describe a life-cycle event in React?  
A life-cycle event in React refers to the different phases of a component and its state as it goes from being mounted, to being updated, and finally to unmounting. Also referred to as birth/growth/death in our analogy.  

## Explain the details of a Higher Order Component?  
A higher order components are advanced React patterns for designing components that share a similar design or behavior by taking in other components and functions.  

## What are three different ways to style components in React? Explain some benefits of each.  
1. Vanilla CSS - This is the most familiar to us and is essentially bulletproof as it is simply referenced stylesheets being imported into our components with class names.  
2. Sass - We can use the power of Sass and Sass syntax in React with many of the same benefits of CSS as well as the benefits of preprocessing.  
3. CSS-In-JS - This allows us to write CSS directly into our components using JS which provides for easier troubleshooting and true compartmentalization of components.