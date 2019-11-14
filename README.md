
![react-d3-starter](https://user-images.githubusercontent.com/28915/68902630-b8359280-079d-11ea-84a1-55fd270cf86c.png)

A starter kit that uses **Hooks-based** components and D3 version 5 modules.

React and D3 both want to manage the DOM which can be a challenge bringing D3 into a React project. This repo demonstrates how hooks are used to load data for the chart with `d3-fetch` and then to provide a reference to an `<svg>` element. D3 then extends that `<svg>` to produce a simple horizontal bar chart. It is oriented at providing a good start for a CRA project using D3.

The D3 margin convention is used to define margin & svg width and height. React renders the initial svg. D3 extrapolates from that element.

The D3 API is [here](https://github.com/d3/d3/blob/master/API.md)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). The Create React App README is [here](CreateReactApp.md)

Enjoy your D3ing!
