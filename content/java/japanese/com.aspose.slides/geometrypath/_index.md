---
title: GeometryPath
second_title: Aspose.Slides for Java API リファレンス
description: GeometryShape のジオメトリ パスを表します
type: docs
url: /ja/com.aspose.slides/geometrypath/
---
**Inheritance:**  
継承:  
java.lang.Object

**All Implemented Interfaces:**  
実装されているすべてのインターフェイス:  
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

GeometryShape のジオメトリ パスを表します
## Constructors

| Constructor | Description |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | GeometryPath のインスタンスを作成します |
## Methods

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape のジオメトリ パスをパス セグメントの配列として返します。 |
| [removeAt(int index)](#removeAt-int-) | ジオメトリ パスの指定されたインデックスにあるセグメントを削除します。 |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | パスの末尾に直線を追加します |
| [lineTo(float x, float y)](#lineTo-float-float-) | パスの末尾に直線を追加します |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | パスの指定された位置に直線を追加します |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | パスの指定された位置に直線を追加します |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | パスの末尾に立方ベジェ曲線を追加します |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | パスの末尾に立方ベジェ曲線を追加します |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | パスの指定された位置に立方ベジェ曲線を追加します |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | パスの指定された位置に立方ベジェ曲線を追加します |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | パスの末尾に二次ベジェ曲線を追加します |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | パスの末尾に二次ベジェ曲線を追加します |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | パスの指定された位置に二次ベジェ曲線を追加します |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | パスの指定された位置に二次ベジェ曲線を追加します |
| [closeFigure()](#closeFigure--) | このパスの現在の図形を閉じます |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | 次のポイントの位置を設定します。 |
| [moveTo(float x, float y)](#moveTo-float-float-) | 次のポイントの位置を設定します。 |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 指定された円弧をパスに追加します。 |
| [getFillMode()](#getFillMode--) | 塗りつぶしモードを設定します |
| [setFillMode(byte value)](#setFillMode-byte-) | 塗りつぶしモードを設定します |
| [getStroke()](#getStroke--) | ストロークの外観を設定します |
| [setStroke(boolean value)](#setStroke-boolean-) | ストロークの外観を設定します |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

GeometryPath のインスタンスを作成します

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

GeometryShape のジオメトリ パスをパス セグメントの配列として返します。

**Returns:**  
戻り値:  
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ジオメトリ パスの指定されたインデックスにあるセグメントを削除します。

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 削除すべきジオメトリ パスのインデックス。 |
### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

パスの末尾に直線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 直線の終点 |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

パスの末尾に直線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 直線の終点の X 座標 |
| y | float | 直線の終点の Y 座標 |
### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

パスの指定された位置に直線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 終点 |
| index | long | PathData のセグメントのインデックス |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

パスの指定された位置に直線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | ポイントの X 座標 |
| y | float | ポイントの Y 座標 |
| index | long | PathData のセグメントのインデックス |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

パスの末尾に立方ベジェ曲線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 最初の方向点 |
| point2 | java.awt.geom.Point2D.Float | 二番目の方向点 |
| point3 | java.awt.geom.Point2D.Float | 終点 |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

パスの末尾に立方ベジェ曲線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | 最初の方向点の X 座標 |
| y1 | float | 最初の方向点の Y 座標 |
| x2 | float | 二番目の方向点の X 座標 |
| y2 | float | 二番目の方向点の Y 座標 |
| x3 | float | 終点の X 座標 |
| y3 | float | 終点の Y 座標 |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

パスの指定された位置に立方ベジェ曲線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 最初の方向点 |
| point2 | java.awt.geom.Point2D.Float | 二番目の方向点 |
| point3 | java.awt.geom.Point2D.Float | 終点 |
| index | long | PathData のセグメントのインデックス |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

パスの指定された位置に立方ベジェ曲線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | 最初の方向点の X 座標 |
| y1 | float | 最初の方向点の Y 座標 |
| x2 | float | 二番目の方向点の X 座標 |
| y2 | float | 二番目の方向点の Y 座標 |
| x3 | float | 終点の X 座標 |
| y3 | float | 終点の Y 座標 |
| index | long | PathData のセグメントのインデックス |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

パスの末尾に二次ベジェ曲線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 方向点 |
| point2 | java.awt.geom.Point2D.Float | 終点 |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

パスの末尾に二次ベジェ曲線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | 方向点の X 座標 |
| y1 | float | 方向点の Y 座標 |
| x2 | float | 終点の X 座標 |
| y2 | float | 終点の Y 座標 |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

パスの指定された位置に二次ベジェ曲線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 方向点 |
| point2 | java.awt.geom.Point2D.Float | 終点 |
| index | long | PathData のセグメントのインデックス |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

パスの指定された位置に二次ベジェ曲線を追加します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | 方向点の X 座標 |
| y1 | float | 方向点の Y 座標 |
| x2 | float | 終点の X 座標 |
| y2 | float | 終点の Y 座標 |
| index | long | PathData のセグメントのインデックス |
### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

このパスの現在の図形を閉じます

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

次のポイントの位置を設定します。

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | ポイントの位置 |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

次のポイントの位置を設定します。

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | ポイントの X 座標 |
| y | float | ポイントの Y 座標 |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

指定された円弧をパスに追加します。

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | 矩形の幅 |
| heigth | float | 矩形の高さ |
| startAngle | float | 開始角度。 |
| sweepAngle | float | スイープ角度/ |
### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

塗りつぶしモードを設定します

**Returns:**  
戻り値:
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

塗りつぶしモードを設定します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

ストロークの外観を設定します

**Returns:**  
戻り値:
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

ストロークの外観を設定します

**Parameters:**  
パラメーター:
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |