---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /zh-hant/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

表示 GeometryShape 的幾何路徑
## 方法

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | 傳回 GeometryShape 的幾何路徑，作為路徑段陣列。 |
| [removeAt(int index)](#removeAt-int-) | 在幾何路徑的指定索引處移除段。 |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | 在路徑的末端新增直線 |
| [lineTo(float x, float y)](#lineTo-float-float-) | 在路徑的末端新增直線 |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | 在路徑的指定位置新增直線 |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | 在路徑的指定位置新增直線 |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | 在路徑的末端新增立方貝塞爾曲線 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | 在路徑的末端新增立方貝塞爾曲線 |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | 在路徑的指定位置新增立方貝塞爾曲線 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | 在路徑的指定位置新增立方貝塞爾曲線 |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | 在路徑的末端新增二次貝塞爾曲線 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | 在路徑的末端新增二次貝塞爾曲線 |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | 在路徑的指定位置新增二次貝塞爾曲線 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | 在路徑的指定位置新增二次貝塞爾曲線 |
| [closeFigure()](#closeFigure--) | 關閉此路徑的目前圖形 |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | 設定下一個點的位置。 |
| [moveTo(float x, float y)](#moveTo-float-float-) | 設定下一個點的位置。 |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 將指定的弧線附加到路徑。 |
| [getFillMode()](#getFillMode--) | 設定填充模式 |
| [setFillMode(byte value)](#setFillMode-byte-) | 設定填充模式 |
| [getStroke()](#getStroke--) | 設定筆劃外觀 |
| [setStroke(boolean value)](#setStroke-boolean-) | 設定筆劃外觀 |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


傳回 GeometryShape 的幾何路徑，作為路徑段陣列。

**傳回值:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


在幾何路徑的指定索引處移除段。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 應刪除的幾何路徑索引。 |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```


在路徑的末端新增直線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | android.graphics.PointF | 線段的終點 |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


在路徑的末端新增直線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 線段終點的 X 座標 |
| y | float | 線段終點的 Y 座標 |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```


在路徑的指定位置新增直線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | android.graphics.PointF | 終點 |
| index | long | PathData 中段的索引 |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


在路徑的指定位置新增直線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 點的 X 座標 |
| y | float | 點的 Y 座標 |
| index | long | PathData 中段的索引 |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


在路徑的末端新增立方貝塞爾曲線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 第一個方向點 |
| point2 | android.graphics.PointF | 第二個方向點 |
| point3 | android.graphics.PointF | 終點 |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


在路徑的末端新增立方貝塞爾曲線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x1 | float | 第一個方向點的 X 座標 |
| y1 | float | 第一個方向點的 Y 座標 |
| x2 | float | 第二個方向點的 X 座標 |
| y2 | float | 第二個方向點的 Y 座標 |
| x3 | float | 終點的 X 座標 |
| y3 | float | 終點的 Y 座標 |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


在路徑的指定位置新增立方貝塞爾曲線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 第一個方向點 |
| point2 | android.graphics.PointF | 第二個方向點 |
| point3 | android.graphics.PointF | 終點 |
| index | long | PathData 中段的索引 |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


在路徑的指定位置新增立方貝塞爾曲線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x1 | float | 第一個方向點的 X 座標 |
| y1 | float | 第一個方向點的 Y 座標 |
| x2 | float | 第二個方向點的 X 座標 |
| y2 | float | 第二個方向點的 Y 座標 |
| x3 | float | 終點的 X 座標 |
| y3 | float | 終點的 Y 座標 |
| index | long | PathData 中段的索引 |
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```


在路徑的末端新增二次貝塞爾曲線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 方向點 |
| point2 | android.graphics.PointF | 終點 |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


在路徑的末端新增二次貝塞爾曲線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x1 | float | 方向點的 X 座標 |
| y1 | float | 方向點的 Y 座標 |
| x2 | float | 終點的 X 座標 |
| y2 | float | 終點的 Y 座標 |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```


在路徑的指定位置新增二次貝塞爾曲線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 方向點 |
| point2 | android.graphics.PointF | 終點 |
| index | long | PathData 中段的索引 |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


在路徑的指定位置新增二次貝塞爾曲線

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x1 | float | 方向點的 X 座標 |
| y1 | float | 方向點的 Y 座標 |
| x2 | float | 終點的 X 座標 |
| y2 | float | 終點的 Y 座標 |
| index | long | PathData 中段的索引 |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


關閉此路徑的目前圖形
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```


設定下一個點的位置。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | android.graphics.PointF | 點的位置 |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


設定下一個點的位置。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 點的 X 座標 |
| y | float | 點的 Y 座標 |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


將指定的弧線附加到路徑。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| width | float | 矩形的寬度 |
| heigth | float | 矩形的高度 |
| startAngle | float | 起始角度。 |
| sweepAngle | float | 掃描角度/ |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


設定填充模式

**傳回值:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


設定填充模式

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


設定筆劃外觀

**傳回值:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


設定筆劃外觀

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |