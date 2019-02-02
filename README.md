[![Follow on Twitter](https://img.shields.io/twitter/follow/pownjs.svg?logo=twitter)](https://twitter.com/pownjs)

# Pown.js

The goal of Pown.js is to rapidly create information security tools and develop new security testing and detection techniques by taking advantage of the vast JavaScript software eco-system.

## Start

The only prerequisite is Node. Install pown the same way all other global modules are installed.

```sh
$ npm install -g pown@latest
```

## Update

We are constantly releasing new features. The following command will help you update.

```sh
$ pown update
```

## History

> [@pdp](https://twitter.com/pdp): Pown.js was started in early 2017 as a collection of scripts to scratch a personal itch. At that time I was busy with setting up [SecApps](https://secapps.com) and I had a lot of useful snippets all over the code-base which I wanted to share as an opensource code. So Pown.js was started.
>
> While the project started in 2017, versions ~0 and ~1 don't have much to show for. The tooling was sort of integrated with the capabilities of SecApps and as a result, it appeared more of extension to a commercial penetration testing software then an opensource project with a life of its own. In Late 2018 and early 2019, the project took a completely different direction with version ~2. Pown is now a lot more independent and set for success.
>
> While you may find that Pown is covering areas already covered by other tools, the goal is not to just recreate them in JavaScript but to make them better. This is easier said than done but I believe with some nurture it is possible to speed them up and open their orignal design to more oportunities. Pown provides a set of core libraries that are designed with performance in mind so that helps when building the tools.
>
> The main philosophy behind Pown.js is that everything must run independently as much as possible so that code can be used outside of Pown itself. This anti-framework approach if you like. In fact, you can build your own tool in JavaScript and then add a single line to your `package.json` file with reference to your command line options to make it available in pown. Pown will do the rest.

## Versions

* **2x Fury** - rapid, breaking changes
* **1x Proto** - largely experimental
* **8x Alpha** - the beginnings

## Logos

Feel free to use the following logs as you see fit.

### Variant 1 (pownjs.com)

```
88888b.   .d88b.  888  888  888 88888b.  
888 "88b d88""88b 888  888  888 888 "88b 
888  888 888  888 888  888  888 888  888 
888 d88P Y88..88P Y88b 888 d88P 888  888 
88888P"   "Y88P"   "Y8888888P"  888  888 
888                                   
888        JS                         
888                                     
```

### Variant 2 (pown credits)

```
+----------------------------------------------+
|                                              |
|   88888b.   .d88b.  888  888  888 88888b.    |
|   888 "88b d88""88b 888  888  888 888 "88b   |
|   888  888 888  888 888  888  888 888  888   |
|   888 d88P Y88..88P Y88b 888 d88P 888  888   |
|   88888P"   "Y88P"   "Y8888888P"  888  888   |
|   888    d8b                                 |
|   888    Y8P                                 |
|   888                                        |
|         8888 .d8888b                         |
|         "888 88K                             |
|          888 "Y8888b.                        |
|          888      X88                        |
|          888  88888P'                        |
|          888                                 |
|         d88P                                 |
|       888P"                                  |
|                                              |
+----------------------------------------------+
```

## License

All modules are published under the MIT license.

```
MIT License

Copyright (c) 2017-2019 pownjs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
