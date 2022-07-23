# About the OkSo App

[![OkSo App](https://okso.app/banner.png)](https://okso.app)

## TL;DR

> The [OkSo](https://okso.app) app is the drawing app to express, grasp, and organize your thoughts and ideas. Draw to explain. Draw to grasp.

## Concept

Some of you are visual learners. You need to see pictures and visualizations **to explain** and **grasp** concepts. You keep a **pencil** and a **piece of paper** at hand. Sometimes it feels like connecting two circles with an arrow would speak more apparent than describing such circles' relationship with words. Visualizations, drawings, and sketches help you organize your thoughts and knowledge.

![okso.app demo](https://raw.githubusercontent.com/trekhleb/okso.app/main/assets/demo/demo-01-0.png)

The process of visualization is not always easy. It requires some thinking and energy. That's why you might find yourself taking a deep breath, and saying _"Ok! So..."_ to yourself or your vis-à-vis before diving deep into the concept. That's the reason for **the Thinker** with the **"Ok! So..."** in the logo.

The **physical paper** or the notepad is good but it has its limitations:

- You may forget it at home.
- The page space might not be enough to contain all the details.
- Often you only have pens of one or two colors.
- If you made a typo you can't just undo/redo it, the sketch is not really editable.

The **OkSo** app tries to overcome these limitations and gives users the possibility to "Draw to explain" and "Draw to grasp".

## Features

The limitations mentioned above are being addressed as follows:

- The [OkSo](https://okso.app) app is available online and thus it is always with you. _Currently, you may export all your drawings to the file and share them between devices manually (i.e. via Google Docs or Dropbox). All your drawings are stored in your browser. We don't send your data to the back-end. The possibility to automatically sync your drawings between devices is in our [Roadmap](https://feedback.okso.app/)._
- It gives you an "infinite" canvas.
- No color limits.
- You may edit your drawings and undo/redo your edits.

![okso.app demo](https://raw.githubusercontent.com/trekhleb/okso.app/main/assets/demo/demo-06.png)

Many online drawing apps give you these (and not only) possibilities. Take a look at [tldraw](https://www.tldraw.com/) or [excalidraw](https://excalidraw.com/), for example. These apps are awesome! Even more, the [OkSo](https://okso.pp) app is built on top of the [@tldraw/tldraw](https://www.npmjs.com/package/@tldraw/tldraw) NPM package itself.

However, what the OkSo app tries to do on top of that is to experiment with the way you **organize your drawings**. It uses the concept of **nested pages**. The page (to be more precise the link to a page) is a first-class citizen of your drawing along with other shapes like freehand curves, rectangles, ellipses, or texts. So you may embed/draw _links to sub-pages inside the page_. It means that you may organize your drawings in the nested tree structure.

For example, here is one of the variants you may organize your drawings/pages:

```
Root drawing
  ├─ Goals
  │     ├─ 2021
  │     ├─ 2022
  │     └─ ...
  ├─ Career
  └─ Learning
        ├─ Machine Learning
        └─ Algorithms breakdown
              ├─ Binary search
              ├─ Power Set
              └─ ...
```

Each item in this tree is a separate drawing/page itself. The **content** of each page might be anything you are using your notepad for. For example:

- _My 2022 goals_
- _My career plans_
- _The "Drawing App" system design_
- _Binary search algorithm breakdown_
- _Brainstorming the startup ideas_
- _The AI learning path_
- _Logistics for my next trip_
- _You name it..._

The fact that the link to the sub-page is just a regular shape allows you to use **size- and color-coding**, to group the links together, and to easily distinguish them visually.

![okso.app demo](https://raw.githubusercontent.com/trekhleb/okso.app/main/assets/demo/demo-03-0.png)

Also, compared to the flat lists, **you'll not be overwhelmed by a large number of pages**, since they may be organized in a tree structure. You will only see the links to the sub-pages of a particular level. You can "travel" easily between the sub-pages back and forth, deeper and deeper until you find a page you need.

![okso.app demo](https://raw.githubusercontent.com/trekhleb/okso.app/main/assets/demo/demo-04-0.png)

Another approach, that the OkSo app takes compared to the other drawing apps is to be **as simple and as minimalist as possible** (just like your physical notepad). This relates not only to the UI but to the list of tools and features in particular (therefore the rectangle, the ellipse, and the arrow are hidden from the tools panel by default). For example, instead of having a reach collection of primitives, what about just drawing the "DataBase Cylinder" icon from scratch? Yes, one of the real reasons for that is plain simple laziness and desire to code less :D However, I believe, this approach also feels more authentic and artistic. When you use a whiteboard during the technical interview or during the brainstorming you draw such primitives easily, aren't you? Plus, having such basic functionalities as copy-pasting, cloning, and resizing should allow you to deliver your thought fast and easily.

![okso.app demo](https://raw.githubusercontent.com/trekhleb/okso.app/main/assets/demo/demo-05-0.png)

The OkSo app is a **Progressive Web App** (PWA). It means that you may install it on your device (add to your home screen) for faster access (see [the instructions for iOS and MacOS](https://twitter.com/okso_app/status/1550510787382362115) and also [the instructions for Android](https://support.google.com/chrome/answer/9658361?hl=en&co=GENIE.Platform%3DAndroid&oco=1)).

## Demo

Here is a demo of how the okso.app may be used to explain/grasp the idea behind some basic data structures:

![okso.app demo](https://raw.githubusercontent.com/trekhleb/okso.app/main/assets/demo/demo-01.gif)

You may also check the [full demo video on YouTube](https://www.youtube.com/watch?v=2833pSyP2k0) to get more context.

<iframe width="560" height="274" src="https://www.youtube.com/embed/2833pSyP2k0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Feedback

Note, that the app is in its **early beta stage** and some features from our [Roadmap](https://feedback.okso.app/) are still in progress and will be delivered soon.

Meanwhile:

- feel free to [subscribe to the product updates](https://okso.app/subscribe) if you're interested
- [leave feedback](https://feedback.okso.app/feedback) (i.e. suggest a feature or report a bug)
- and [follow OkSo on Twitter](https://twitter.com/okso_app)
