# heighlight-card

基本原理：
高亮边框本质上是通过嵌套盒子实现的。
通过盒子间嵌套和遮罩来实现盒子的边框，然后在为每个盒子定义一个(盒子/伪元素)来实现高亮，然后就是为对应的盒子添加偏移。
添加了便宜之后利用css变量动态设置高亮盒子位置。
然后就是通过js动态计算当前鼠标位置，将位置赋值给每个盒子上。这样就实现了跟随鼠标移动的高亮边框
