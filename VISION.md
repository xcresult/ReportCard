## Project Goals
- Provide a simple way of visualizing Xcode's test results without leaving the web browser
- Provide a way to customize the visualization experience to the developer's needs
- Provide integrations with known CI/CD tools and vendors
- Leverage the scripting power of Swift to build a safer and more reliable experience
- To keep the tool up to date with Xcode releases

## Project Inspiration
With the release of Xcode 11, Apple introduced a lot of great changes to its testing infrastructure, in particular to how all testing artifacts were generated. 

At the same time, the tool we had been using so far, [xcpretty](https://github.com/xcpretty/xcpretty) seemed to be abandoned.

We felt the need to be able to visualize our test results without the need of Xcode and preferably without having to leave GitHub or our CI, so by leveraging the concept of _xcpretty_ with _xcresult_ new capabilities, we felt we could achieve something cool.
