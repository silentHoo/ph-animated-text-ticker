ph-animated-text-ticker
================

This component  gives you the ability to let text slide in an environment where the text hasn't enough
space to be fully shown. You may know that behaviour from some hardware devices like car radios or MP3 players.
When the text hasn't enough space he'll slide with a smooth ease function from right to left in respect to the ratio
between the length of the text string to show and the animation duration. That means the text will slide slower, if
the space is small and the text long.

You can style the text like you want as of every web component you know. Please use the pseudo selectors `::shadow` and
`/deep/` as you prefer. I'll not change any `HTMLElement id` or `class name` within the components `<template>` in the
next minor versions so you can be sure that your component will not break in the upcoming minor versions.

There's also a built-in resize event handler which handles the animations if the user resizes the browser. If there's
enough space available and the user can see all the messages no animation will start, otherwise an animation will be
started.

## 1. Install

`bower install silentHoo/ph-animated-text-ticker`

Run the command above from your project root.

## 2. Import

Import the component by adding this to your HTML file:

`<link rel="import" href="components/ph-animated-text-ticker/ph-animated-text-ticker.html">`

## 3. Use / Demo

See the [component page](http://silentHoo.github.io/ph-animated-text-ticker) for more information.

## License

Copyright (c) 2014-2015 Patrick Hillert. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

1. Redistributions of source code must retain the above copyright
notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above
copyright notice, this list of conditions and the following disclaimer
in the documentation and/or other materials provided with the
distribution.
3. Neither the name of the copyright holder nor the names of its
contributors may be used to endorse or promote products derived from
this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.