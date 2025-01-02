
<link rel='stylesheet' href='https://ise.web.app/load/l.css'>

# **A Re-work Language**

Our the world with the need for software development, we’ve faced many tools, frameworks, and languages, each claiming to offer something new and better. However, all of these things or system mask their true workings behind jargon and abstract concepts. 

Our Company **InShareByte TM** & Our Team **CodeEN**, we’ve built I.S.E (Interface Style En-liner) to challenge that norm. 

We focus on transparency, simplicity, and honesty—creating a language that improves existing technologies like HTML, CSS, and JavaScript while cutting through the complexity that often hinders true development progress.

---

## **Why re-working a Language**

Our language is not just another framework or library. It’s a re-work language, new type of language combining both interpreted and compiled elements, that enhances the traditional development stack. Though some may say it is a "MODULE" or "PACKAGE", Well we transparently prove that we use this so no need to install the language, Import and Use. ISE offers the flexibility of scripting while maintaining the performance of compiled code. Unlike other solutions, ISE doesn’t introduce unnecessary abstraction; instead, it improves the existing languages and tools developers are already using. This makes the language easy to learn while offering powerful features without overcomplicating things.

*Aim to simplify, not just to make things seemed* ***"cool."** Before continuing as we are respectful, we'll pre-apologize to call names, Our advocacy is truth and transparent. Not to cause anger or a **'Fight'**.*

While other, like React, introduce complex syntaxes and dependencies, we focus on keeping things real and transparent.

like said by Our Lead Engineer

*We may not 100% Know but we feel it. Like a honeypot feeling, you thought it was a discount but it is stolen*

---

## **A Language, Just Import**

ISE is a language. Like a framework? Maybe. Some may say it's just 'A module', some may say "A package." We use the module you can load just like a normal HTML script tag. By importing the ISE module "CDN," you unlock the full power of the ISE language within your application easily, using `.html` or `.ise`. You can load ISE files or even plain HTML with the ISE module, which will give you access to all its features without requiring complex setup processes or dependencies.

To use ISE, simply import the module hosted on our server (not some jargon-laden CDN term, but a real cloud-hosted file that’s always available). This is what makes ISE different—it’s honest, transparent, and as simple as using any other web script, but with a lot more flexibility and control.

```html
<script src="https://ise.web.app/load/l.js"></script>
```

From there, you’re ready to dive into the ISE language and create dynamic, fast-loading applications across platforms.

---

## **Honesty of Rendering cuz It Is Preloading, Prechunk, Not Server-Side**

Again Before we go further, we want to apologize for being honest and we hope this is understood as part of our commitment to transparency. Frameworks like Next.js or React often claim they provide “server-side rendering,” but the reality is different. What’s actually happening is preloading or pre-chunking files before sending them to the client. These terms are not the same as true server-side rendering, but the industry often mixes them up to sound more sophisticated.

When we say server-side rendering, we mean that when you visit a site, the server should provide a fully rendered and ready-to-display page. ISE doesn’t hide behind these terms. We use preloading to achieve speed and efficiency. Files are served from the cloud, not pre-rendered on the server, making the process much faster but without the confusing terminology that often misleads developers.

---

## **Not Classes, and Why we use Attributes, The Real Difference**

One of the points we’ve been vocal about is the overuse of classes in CSS frameworks like Tailwind. In Tailwind, you’re encouraged to add multiple classes to style elements. While this may seem convenient, it’s actually slower when compared to using HTML attributes.

**Reason why.**
in the HTML element hierarchy, attributes are faster because they are closer to the core of the element. When you load an element, it’s processed in the following order:

1. HTML
2. HTML Body
3. HTML Element
4. HTML Attributes
5. HTML Class Attribute
6. HTML Class Value

The further you go down the hierarchy, the slower it becomes. Classes, being further down in the hierarchy, create more work for the browser, slowing down rendering. That’s why ISE uses attributes instead of classes. By sticking to attributes, we avoid unnecessary complexity and ensure faster performance without sacrificing flexibility.

So while Tailwind relies on class names to handle styling, ISE keeps things simple and efficient by using attributes. The result? Faster load times and more efficient rendering. It’s not about looking cool or using the latest buzzword; it’s about creating a faster, more efficient experience for developers and users alike.

---

## **The Role of the ISE Viewer for A Lightweight Native Solution**

The ISE Viewer is at the heart of the ISE ecosystem. It lets users easily view and run ISE-based applications on Windows, Linux, and Android platforms. Unlike frameworks like Electron that rely on Chromium to run apps, the ISE Viewer is built using C and half Assembly, making it lightweight, fast, and resource-efficient.

ISE’s web view is coded in C and Assembly, which gives us control over performance and resource usage. Unlike other solutions, we avoid the overhead of Chromium or Other in the ISE Viewer. We also want to be upfront about our approach this web view is ours. It’s custom-built, not borrowed from another browser engine.

In the future, we plan to move to Firefox to further improve the viewer. This decision aligns with our long-term goal of providing the best possible experience while keeping things open and transparent.

---

## **ISE v1.5, Current Phase and Challenges**

We’re continuously working on improving ISE. However, as with any evolving technology, there are challenges we must face. One of the current limitations in ISE 1.5 is related to CSS chunking. When you load an ISE-based application, all the CSS is loaded at once, which can lead to some layout shifts or performance issues on certain devices. Despite having the best practices on Google's Lighthouse (100% performance score), the issue of CSS chunking remains a challenge.

This challenge occurs because we load all the CSS upfront instead of dynamically loading only what is necessary. While ISE adheres to the best standards and practices in terms of performance, we are aware that our approach leads to higher layout shifts and less-than-optimal CSS loading. This is partly due to the current funding limitations and our ongoing focus on version 2.0.

In ISE 2.0, we are planning a major update to resolve these issues. The new system will work similarly to how Tailwind handles classes—only the relevant CSS for each element will be loaded as needed. For example, when you load an element, only the CSS for that element will be applied, rather than loading all CSS files upfront. This dynamic CSS loading will improve performance and reduce layout shifts significantly.

---

## **How to Use ISE: Simplifying Development Across Platforms**

Getting started with ISE is straightforward. Developers can use ISE files (or even just plain HTML) and import the ISE module to get started. From there, running the application on any platform is as easy as calling the correct command.

To download and run the ISE Viewer for different platforms, developers simply need to use:

```html
<script src="https://ise.web.app/load/l.js"></script>
<script>
ise.get.win(); 
ise.get.lin(); 
ise.get.and(); 
</script>
```


| **This download Android `Ise Viewer`** |
|----------------------------------------|
| `ise.get.and();`                       |

| **This one downloads Linux `Ise Viewer`** |
|-------------------------------------------|
| `ise.get.lin();`                         |

| **This download Windows `Ise Viewer`** |
|----------------------------------------|
| `ise.get.win();`                        |

This direct, cross-platform solution ensures that applications powered by ISE can be easily deployed on multiple devices without the need for complicated setup processes or additional dependencies. Simply put, we believe simplicity is the future of development, and we’re making sure ISE stays true to that vision.

---

## **Reimagining the Future of Development**

ISE is more than just a language; it’s an evolution of how we approach software development. From web apps to desktop applications and even operating systems, ISE can handle it all. While other languages and frameworks complicate the process, we’ve worked to make things simpler. You don’t need a terminal or complicated setup to get started with ISE. Simply create an ISE file, import the module, and you’re ready to go.

By focusing on transparency, efficiency, and real performance, ISE offers a powerful alternative to the convoluted, over-engineered solutions many developers face today. We’re here to show that it’s possible to build sophisticated applications with clarity, efficiency, and simplicity.

---
