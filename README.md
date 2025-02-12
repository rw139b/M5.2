# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```
## Questions

Color was Green/Green/black, I fixed colors and made it readable

Images were fixed by adding alt text

For audio I included a transcript and added a download for older browsers

I added a label element with the aria-label attribute for screen readers.

To make sure each input field is correctly associated with its label I used the for attribute in the 
label that matches the id of the corresponding input, this will create an unambiguous connection.

I could not figure out the show/hide keyboard

made the table more readable

two more ideas for accessablity would be making the text larger, and adding text to speech for 
image descriptions.