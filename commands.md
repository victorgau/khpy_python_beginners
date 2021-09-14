# turtle常用指令彙整

在這裡我們列出一些繪圖指令之外的常用指令，若想要了解更詳細的指令使用方法可以點擊[官網連結](https://docs.python.org/3/library/turtle.html)進一步查詢。


## 基本繪圖指令

|方法|縮寫|說明|
|:-|:-|:-|
|forward(100)|fd(100)|前進100步。|
|backward(100)|back(100)或bk(100)|退後100步。|
|left(90)|lt(90)|向左轉90度。|
|right(90)|rt(90)|向右轉90度。|
|circle(50)||畫一個半徑為 50 的圓, 圓心在 turtle 左邊。|
|home( )||回到原點 (0, 0)，turtle的角度設回 0。|
|goto(x, y)||移動到 (x, y) 位置。|
|penup( )|pu( )或up( )|提起畫筆，停止畫圖。|
|pendown( )|pd( )或down( )|放下畫筆，開始畫圖。|
|dot(5)||在目前的位置，畫一個5 pixels寬的點。|

## 設定畫筆粗細及顏色

|方法|說明|
|:-|:-|
|bgcolor('green')|設定背景顏色為綠色。|
|pencolor('red')|設定畫筆顏色為紅色。|
|fillcolor('yellow')|設定填滿顏色為黃色。|
|begin_fill( )|開始填滿顏色。|
|end_fill( )|結束填滿顏色。|
|pensize(10)|設定線的寬度為 10。|
|width(10)|設定線的寬度為 10。|


## 回傳海龜(turtle)的狀態

|方法|縮寫|說明|
|:-|:-|:-|
|heading( )||回傳 turtle 的方向。|
|position( )|pos()|回傳 turtle 的位置。|
|towards(x, y)||回傳目前位置跟 (x, y) 之間的角度。|
|xcor( )||回傳目前的 X 座標。|
|ycor( )||回傳目前的 Y 座標。|
|distance( )||回傳目前位置跟 (x, y) 的距離。|

## 其他控制

|方法|說明|
|:-|:-|
|stamp()|在目前的位置蓋一個turtle形狀的章。|
|shape('turtle')|可以是‘arrow’, ‘classic’, ‘turtle’ 或 ‘circle’|

## 生成turtle跟screen

|方法|說明|
|:-|:-|
|Turtle( )|產生一個 turtle 物件。|
|Screen(width, height)|設定繪圖螢幕的大小，如果省略 width 跟 height，則將大小設為預設值。|