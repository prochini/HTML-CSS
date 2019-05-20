## transition

```css
#box1 {
background:;
width: 150px;
height: 100px;
text-align: center;
line-height: 100px;
transition: all 1s;
border: 10px solid;
}

#box1:hover{
    background: yellow;
color: white;
cursor: pointer;
width: 200px;
height: 200px;

}
#box2{
    margin: 10px;
    width: 100px;
height: 100px;
    background: pink;

}

```
## Die Verwandlung：transform
```css
#box1 {
background:pink;
width: 150px;
height: 100px;
border-radius: 30px;
text-align: center;
line-height: 100px;
color:white;
font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
position: absolute;
top: 50%;
left :50%;
transform: translate(-50%, -50%);
}
```
## box model



```css
#box1 {
background:pink;
width: 200px;
height: 100px;
border-radius: 30px;
text-align: center;
line-height: 100px;
color:white;
font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
border:5px solid salmon;
padding: 10px;
box-sizing: border-box; //自動把border、padding算進去
}
```

## inline-block

```css
#box {
background:pink;
width: 50px;
height: 50px;
MARGIN: 10px;
display:inline-block; // 對外像 inline 可併排，對內像 block 可調各種屬性
display:block; // 一個佔據一行
display:inline; // 不能調寬高。不能調上下邊距
}
```
