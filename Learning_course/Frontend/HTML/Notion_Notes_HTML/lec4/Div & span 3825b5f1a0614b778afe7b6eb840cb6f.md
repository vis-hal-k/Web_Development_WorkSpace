# Div & span

Both the tags (**[<div>](https://www.geeksforgeeks.org/div-tag-html/)** and **[<span>](https://www.geeksforgeeks.org/span-tag-html/)** ) are used to represent the part of the webpage, <div> tag is used a as block part of the webpage and <span> tag is used as a inline part of the webpage like below:

<div> tag 

Example:

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled.png)

<span> tag [inline element]

Example:

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%201.png)

---

---

---

```html
<div style="border:1px solid red;"> This is <strong>DIV</strong> which take whaole area </div>
<br>
<span style="border:1px solid Black;"> This is<strong>SPAN</strong> which takes inline area.</span>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%202.png)

## ***<iframe> Tag***

It is use to put another Html document( website ) in our html document.

```html
<iframe src = "https://www.ndtv.com/"  height ="500"  width = "500" > </iframe> 
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%203.png)

## ***<audio> Tag***

To embed audio .

```html
<audio controls>
</audio>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%204.png)

To embed or playing song.
We need to use *<source> tag  with src attributes or type attributes. And* 
if sometimes audio is disabled and you want to put msg to user  see below example :

```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%205.png)

## ***Video Tag***

```html
<video controls>

</video>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%206.png)

example

```html
<video controls>
<source src ="video.mp4" type="video/mp4">
</video>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%207.png)

Instead of control we can use some attribute *autoplay* *width height controls*  

## PDF embed tag

PDF embeded by three tag :

- embed tag
- iframe
- object

### Embed

```html
<embed src="pdf.pdf" type="application/pdf" width="500" height="500">
```

### iframe

```html
<iframe src = "pdf.pdf" width = "800" height = "100">
</iframe>
```

### object

```html
<object data="pdf.pdf" type="application/pdf" width="800" height="100">
</object>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%208.png)

## *Embed Youtube video*

 

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/6gHy5kLjlvw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%209.png)

## *Embed Google map*

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d28973.60803912487!2d84.99341879999997!3d24.805689799999993!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39f32a6f75281831%3A0x666e0ca18559943d!2sDangi%20Nagar%2C%20Kharkhura%2C%20Gaya%2C%20Bihar%20823002!5e0!3m2!1sen!2sin!4v1657331946982!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%2010.png)

## ***Html Entities***

In HTML we have some reserved Entities exapmle : In body you write something it will show in website.

But if you want write reserved Entities( tag name ) → <div> <span>

```html
//Write HTML entites using name 
<body>
&name ;
&lt;div&gt; // lt -> < or gt -> >
</body>
//Write HTML entites using Number 
<body>
&#number ;
&#60;body&#62;
</body>
```

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%2011.png)

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%2012.png)

![Untitled](Div%20&%20span%203825b5f1a0614b778afe7b6eb840cb6f/Untitled%2013.png)

### Non breaking space :

&nbsp ;

```html
hello&nbsp;World
```

## ***Html symbol and symbol***

By using Html entities by name and Number 

`&copy;` → ©

`&lt;` → <

In genral search in google

`&#128516;` → 🙂

###