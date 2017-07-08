## 第一章 认识HTML - Web语言

### HTML文档标记

```html
<html>
    <head>
        <title> 页面标题 </title>
    </head>

    <body>
        <h1> 标题1 </h1>  
        <h2> 标题2 </h2>  
        <p> 这是一个段落 </p>
    </body>
</html>
```

### 认识style元素

```html
<html>
    <head>
        <title> 页面标题 </title>
        <style type="text/css">
        </style>
    </head>
</html>
```

## 第二章 深入了解超文本 - 认识HTML中的“HT”

- <a>元素用于创建指向另一个页面的链接  

```html
<a>elixirs</a>
<a href="beverages/elixir.html">elixirs</a>
<a href="../lounge.html">Back to the Lounge</a>
```

- 了解属性  

```html
<a href="beverages/elixir.html">elixirs</a>
<img src="images/drinks.gif">
```

## 第三章 构建模块 - Web页面建设

### 引用<q>和<blockquote>

- \<q> 是inline元素
- \<blockquote>是块元素  

```html
    <p>
       Just the essentials.  As
      Lao Tzu would have said, <q>A journey of a 
      thousand miles begins with one Segway.</q>
    </p>
```

```html
    </p>
    <blockquote>
      Passing cars, <br>
      When you can't see, <br>
      May get you, <br>
      A glimpse, <br>
      Of eternity. <br>
    </blockquote>
    <p>
```

\<br>是void元素，用于换行。

### 列表

**注释**  
> ul = unordered list  
> ol = ordered list  
> li = list item  

- 无序列表  

```html
    <ul>
      <li>cellphone</li> 
      <li>iPod</li>
      <li>digital camera</li>
      <li>and a protein bar</li>
    </ul>
```

- 有序列表  

```html
    <ol>
      <li>Walla Walla, WA</li> 
      <li>Magic City, ID</li> 
      <li>Bountiful, UT</li>
      <li>Last Chance, CO</li>
      <li>Truth or Consequences, NM</li>
      <li>Why, AZ</li> 
    </ol>
```

## 第四章 连接起来 - Web镇之旅

### 完善链接

- 使用id属性为<a>创建目标  
- 使用title属性为所要链接的页面增加文本描述  

**http://wickedlysmart.com/buzz.html**

```html
<h3 id="Coffee">Coffee</h3>
<p>
<i>All fluid ounces are U.S. fluid ounces.</i>
</p>
```

**index.html**
```html
	<p>
		Read the <a href="http://wickedlysmart.com/buzz/#Coffee"
		            title="Read all about caffeine on the Buzz">Caffeine Buzz</a>.
	</p>
```


