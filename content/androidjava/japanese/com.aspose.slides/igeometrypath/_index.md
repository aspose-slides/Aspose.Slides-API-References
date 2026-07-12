---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /ja/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

GeometryShape のジオメトリ パスを表します
## メソッド

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape のジオメトリ パスをパス セグメントの配列として返します。 |
| [removeAt(int index)](#removeAt-int-) | ジオメトリ パスの指定されたインデックスにあるセグメントを削除します。 |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | パスの末尾に線を追加します。 |
| [lineTo(float x, float y)](#lineTo-float-float-) | パスの末尾に線を追加します。 |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | パスの指定された位置に線を追加します。 |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | パスの指定された位置に線を追加します。 |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | パスの末尾に立方ベジェ曲線を追加します。 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | パスの末尾に立方ベジェ曲線を追加します。 |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | パスの指定された位置に立方ベジェ曲線を追加します。 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | パスの指定された位置に立方ベジェ曲線を追加します。 |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | パスの末尾に二次ベジェ曲線を追加します。 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | パスの末尾に二次ベジェ曲線を追加します。 |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | パスの指定された位置に二次ベジェ曲線を追加します。 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | パスの指定された位置に二次ベジェ曲線を追加します。 |
| [closeFigure()](#closeFigure--) | このパスの現在の図形を閉じます。 |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | 次の点の位置を設定します。 |
| [moveTo(float x, float y)](#moveTo-float-float-) | 次の点の位置を設定します。 |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 指定された弧をパスに追加します。 |
| [getFillMode()](#getFillMode--) | 塗りつぶしモードを設定します。 |
| [setFillMode(byte value)](#setFillMode-byte-) | 塗りつぶしモードを設定します。 |
| [getStroke()](#getStroke--) | ストロークの外観を設定します。 |
| [setStroke(boolean value)](#setStroke-boolean-) | ストロークの外観を設定します。 |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

GeometryShape のジオメトリ パスをパス セグメントの配列として返します。

**戻り値:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ジオメトリ パスの指定されたインデックスにあるセグメントを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべきジオメトリ パスのインデックス。 |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

パスの末尾に線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | android.graphics.PointF | 線の終点 |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

パスの末尾に線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 線の終点の X 座標 |
| y | float | 線の終点の Y 座標 |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

パスの指定された位置に線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | android.graphics.PointF | 終点 |
| index | long | PathData のセグメントのインデックス |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

パスの指定された位置に線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 点の X 座標 |
| y | float | 点の Y 座標 |
| index | long | PathData のセグメントのインデックス |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

パスの末尾に立方ベジェ曲線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 最初の制御点 |
| point2 | android.graphics.PointF | 2 番目の制御点 |
| point3 | android.graphics.PointF | 終点 |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

パスの末尾に立方ベジェ曲線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 | float | 最初の制御点の X 座標 |
| y1 | float | 最初の制御点の Y 座標 |
| x2 | float | 2 番目の制御点の X 座標 |
| y2 | float | 2 番目の制御点の Y 座標 |
| x3 | float | 終点の X 座標 |
| y3 | float | 終点の Y 座標 |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

パスの指定された位置に立方ベジェ曲線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 最初の制御点 |
| point2 | android.graphics.PointF | 2 番目の制御点 |
| point3 | android.graphics.PointF | 終点 |
| index | long | PathData のセグメントのインデックス |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

パスの指定された位置に立方ベジェ曲線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 | float | 最初の制御点の X 座標 |
| y1 | float | 最初の制御点の Y 座標 |
| x2 | float | 2 番目の制御点の X 座標 |
| y2 | float | 2 番目の制御点の Y 座標 |
| x3 | float | 終点の X 座標 |
| y3 | float | 終点の Y 座標 |
| index | long | PathData のセグメントのインデックス |
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

パスの末尾に二次ベジェ曲線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 制御点 |
| point2 | android.graphics.PointF | 終点 |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

パスの末尾に二次ベジェ曲線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 | float | 制御点の X 座標 |
| y1 | float | 制御点の Y 座標 |
| x2 | float | 終点の X 座標 |
| y2 | float | 終点の Y 座標 |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

パスの指定された位置に二次ベジェ曲線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 制御点 |
| point2 | android.graphics.PointF | 終点 |
| index | long | PathData のセグメントのインデックス |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

パスの指定された位置に二次ベジェ曲線を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 | float | 制御点の X 座標 |
| y1 | float | 制御点の Y 座標 |
| x2 | float | 終点の X 座標 |
| y2 | float | 終点の Y 座標 |
| index | long | PathData のセグメントのインデックス |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

このパスの現在の図形を閉じます。
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

次の点の位置を設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | android.graphics.PointF | 点の位置 |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

次の点の位置を設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 点の X 座標 |
| y | float | 点の Y 座標 |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

指定された弧をパスに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | float | 矩形の幅 |
| heigth | float | 矩形の高さ |
| startAngle | float | 開始角度 |
| sweepAngle | float | 掃過角度 |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

塗りつぶしモードを設定します。

**戻り値:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

塗りつぶしモードを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

ストロークの外観を設定します。

**戻り値:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

ストロークの外観を設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |