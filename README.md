# Module collisions

<a name=".CollidePointInRect"></a>
### Function CollidePointInRect:Bool(px:Float, py:Float, x:Float, y:Float, w:Float, h:Float)

Return true if point **px,py** is in rectangle **x,y,w,h**

<a name=".CollideRectInRect"></a>
### Function CollideRectInRect:Bool(x1:Float, y1:Float, w1:Float, h1:Float, x2:Float, y2:Float, w2:Float, h2:Float)

Return true if rectangle **x1,y1,w1,h1** is in rectangle **x2,y2,w2,h2**

<a name=".CollideCircleInRect"></a>
### Function CollideCircleInRect:Bool(cx:Float, cy:Float, r:Float, x:Float, y:Float, w:Float, h:Float)

Return true if circle at **cx,cy** with radius **r** is in rectangle **x,y,w,h**

<a name=".CollideCircleInCircle"></a>
### Function CollideCircleInCircle:Bool(x1:Float, y1:Float, r1:Float, x2:Float, y2:Float, r2:Float)

Return true if circle at **x1,y1** with radius **r1** is in circle at **x2,y2** with radius **r2**

