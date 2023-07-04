# 2022-10-25-Markdown的好看的HTML.md


## 使用

在 md 的开始加入引用的 css

```html

<link rel="stylesheet" type="text/css" href="https://darian.top/Darian1996/demo/2022/css/MarkdownHTML.css">

```


---

## 代办列表

- [ ] 未完成
- [ ] 未完成
- [ ] 未完成
- [x] 完成
- [x] 完成
- [x] 完成

## 顺序列表

- 一级
- 一级
- 一级
  - 二级
  - 二级
  - 二级
    - 三级
    - 三级
    - 三级


---

1. 第一
2. 第二

> 序号展示不对

---

# 一级标题页

## 格式抄袭链接

**[keevolAbout](https://www.keevol.cn/about.html)  ** ｜  [keevolAbout](https://www.keevol.cn/about.html)  

---

下边是 html 直接复制粘贴就行了

---

Typora 导出为 HTML，记得带格式。

> - HTML
> - HTML(withoutstyles) 。

选择 HTML



<center>居中展示</center>


----
<style>
      body {
          max-width: 52rem;
          padding: 2rem;
          margin: auto;
          font-family: 'Source Han Serif', serif;
          font-size: 21px;
      }
      img {
          max-width:100%;
          max-height:100%;
          display: block;
          text-align: center;
          margin:auto;
      }
      h1 {
        margin-block: 1.2rem;
        font-size: 63px;
      }
      figcaption {
          text-align: center;
      }
      nav a, footer div a{
          margin:0px 5px;
          background-image: linear-gradient(
            45deg,
            #e44219,
            #005ff3
          );
          background-clip: text;
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
      }
      p {
        font-size: 27px;
      }
      p, li, h1,h2,h3 {
        background-image: linear-gradient(
          45deg,
          #e44219,
          #005ff3
        );
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }
      .center {
        display: flex;
        justify-content:center;
        align-items:center;
      }
    </style>