title: How to apply canvas animations with vue and konva?
layout: svelte_page

---

Konva itself has two methods for animations [Tween](/docs/tweens/Linear_Easing.html) and [Animation](/docs/animations/Rotation.html). You can apply both of them to nodes manually.

For simple use cases we recommend to use `node.to()` method.

Instructions: Try to move a rectangle.

<iframe src="https://codesandbox.io/embed/github/konvajs/site/tree/master/svelte-demos/simple_animations?hidenavigation=1&view=split&fontsize=10&module=/App.svelte" style="width:100%; height:500px; border:0; border-radius: 4px; overflow:hidden;" sandbox="allow-modals allow-forms allow-popups allow-scripts allow-same-origin"></iframe>
