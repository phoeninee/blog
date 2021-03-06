# The beginning of a new story

> 一切才刚刚开始

一个月前，在刚刚看完[Vue官方教程](https://cn.vuejs.org/v2/guide/)的时候，我就开始了写一个博客网站的计划。一个月之后的现在，这个网站拥有了基本的功能了。

尽管博客很简单，但在整个过程中我是尽量写出可以复用的组件，花了不少时间考虑。且主要也是为了熟悉尽可能多的`Vue`的属性。复用组件在此[phoeninee/phoenine/src/extension](https://github.com/phoeninee/Phoenine/tree/master/src/extension)。

当然我也在页面设计上花了不少时间。在一个星期前经历了一次改版，之前写的有一些没用了。另外在`css`类名命名，以及复用的方面做得不够好。还有不少细节还需改善。

## Vue

关于Vue，一开始选择它是据说它简单易学。而在看教程的过程中我也体会到了它的精妙。

每个组件作为应用的单位，以模板，代码，样式为一体，实现内部聚合，又通过组件间的通信（`props`，事件触发传递）使得各个组件能各自很好的联系起来，又不至于过度耦合。（当然在，使用的过程中也有可能会处理不当，使耦合加深，比如：直接修改通过`props`传递的数组，或对象）。

此外，还有各种`API`，选项，实例属性、方法，指令等。

这个博客是我的第一个Vue项目。虽然简单，但能用这个工具做出合心意的网站，很开心。这也是进一步学习`Vue`的一个不错的开头。对于Vue还有不少需要学习，比如自定义指令。当然最重要的还是关于`Vue`的源码学习。我很期待能啃下这个有点大的语法糖。

## Scss和ElementUI

一开始是用`bootstrap`来写这个网站的。本来已经把`bootstrap`文档过了一遍了。但之后又了解到`ElementUI`。移除bootstrap，看了ElementUI之后，又顺便把`Sass`的文档看了大半。

尽管`scss`写了不少，但都只是些基本的用法，还要好好再去看一遍文档。

至于`ElementUI`，一开始还在感概，这个工具好像很不错的样子。但它毕竟样式是固定的，想要做出自己想要的效果，以及想要好好学习`Vue`用法，还是得自己造组件。在这过程造的组件在这 [phoeninee/phoenine/src/extension](https://github.com/phoeninee/Phoenine/tree/master/src/extension)

## Vue-router

目前只知道是个路由切换，配置动态路径的工具。

## axios

目前是用于请求`api.github.com`的信息，以及在线上获取用户设置信息以及文章信息。

---

在写网站的过程中，我发现一些组件的功能实现起来不难。但想要把各个组件之间的逻辑，以及确保组件的复用性这两个方面确实有不小的难度。我在整个过程中也在这两个方面纠结了许久。现在虽然已经成型，但应该还有不少需要改进的设计。

接下来的计划：

- 实现并移除网站所有与`ElementUI`有关的组件
- 实现留言功能（没头绪）
- 为了符合`Github pages`的静态，写一个生成静态网页的编辑器。

