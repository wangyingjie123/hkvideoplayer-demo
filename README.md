# hkvideo-player
## 1.安装
```
npm install hkvideo-player
```
## 2.使用
```javascript { .theme-peacock } 
1、ES6 Module 引入
import Player from 'hkvideo-player'
const players = new Player({
    id: 'app',
    url: '',
    cssFullscreen: true, // 网页全屏
    fluid: true, // 流式布局
    autoplay,
});
// 2、CDN方式引入
<script src="../browser/index.js" type="text/javascript"></script>
```
## 3.使用文档见
[hkvideo-player使用文档及API，戳这里😄](https://juejin.im/post/6883423886927462413)
