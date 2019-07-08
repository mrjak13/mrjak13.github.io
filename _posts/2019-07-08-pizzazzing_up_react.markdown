---
layout: post
title:      "Pizzazzing up React"
date:       2019-07-08 09:40:50 -0400
permalink:  pizzazzing_up_react
---

Not even half way through my React project and I am staring at this bland, unstyled body of text and links that is adding unnecessary anxiety to my life.  Time for some css! I decided to go with the react-bootstrap library. Setting it up was not too bad. The only hiccup I ran into was where to put the initial <link> and <sript> tags.  After doing a little more digging I realized they go where they always have, in the index.html file.  Just one question.  I haven't seen an index.html file since I started using react.  Time for more digging.  Thankffully I did'nt have to go far.  When setting up using create-react-app there will be a public folder in the top level of the app you created.  There lies your inex.html file.

After installing the packages (npm install react-bootstrap bootstrap) and dealing with the issue above it was smooth sailing.  Documentation was thorough and easy to implement.  Need a fancy button? Import it into your component (import Button from 'react-bootstrap/Button'), now you have access to <Button></Button>.  It's that easy.  Every once in a while I ran into an issue where something was not defined.  For example, when I set up my nav bar, the example came with a dropdown menu.  The <NavDropdown> was causing an error. I couldn't find any documentation on it, but I tried importing (import NavDropdown from 'react-bootstrap/NavDropdown') and wouldn't you know it, it worked.

Now that my project's I's were dotted, T's were croseed, and it was polished with react-bootstrap I was finially finished.  So I thought.  For some reason "let's add animation" popped in my head and I couldn't get reid of it.  Tackling another library and the issues it'll cause is not something I had in mind, but there I went and it wasn't bad at all.  In fact I had zero issues with it.  Keep in mind I only used basic animations (simple fade ins).  Anyway, I used the react-reveal library for the animations.  Install it (npm install react-reveal --save), import your desired animation (import Fade from 'react-reveal/Fade';) Wrap your components in it(<Fade><Component /></Fade>) done...  

I will be forever greatful for these libraries that bring beauty to my hard work.

Happy Coding!
