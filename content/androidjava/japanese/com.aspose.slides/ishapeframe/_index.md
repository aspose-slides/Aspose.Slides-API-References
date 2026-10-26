---
title: IShapeFrame
second_title: Java APIリファレンス – Android 用 Aspose.Slides
description: 形状フレームのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/ishapeframe/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

形状フレームのプロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | フレームの左上隅の X 座標を返します。 |
| [getY()](#getY--) | フレームの左上隅の Y 座標を返します。 |
| [getWidth()](#getWidth--) | フレームの幅を返します。 |
| [getHeight()](#getHeight--) | フレームの高さを返します。 |
| [getRotation()](#getRotation--) | フレームが Z 軸周りに回転した角度（度数）を返します。 |
| [getCenterX()](#getCenterX--) | フレームの中心の X 座標を返します。 |
| [getCenterY()](#getCenterY--) | フレームの中心の Y 座標を返します。 |
| [getFlipH()](#getFlipH--) | フレームが水平方向に反転しているかどうかを判断します。 |
| [getFlipV()](#getFlipV--) | フレームが垂直方向に反転しているかどうかを判断します。 |
| [getRectangle()](#getRectangle--) | フレームの座標を返します。 |
### getX() {#getX--}
```
public abstract float getX()
```


フレームの左上隅の X 座標を返します。読み取り専用 float.

**戻り値:**
float
### getY() {#getY--}
```
public abstract float getY()
```


フレームの左上隅の Y 座標を返します。読み取り専用 float.

**戻り値:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


フレームの幅を返します。読み取り専用 float.

**戻り値:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


フレームの高さを返します。読み取り専用 float.

**戻り値:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


フレームが Z 軸周りに回転した角度（度数）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り専用 float.

**戻り値:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


フレームの中心の X 座標を返します。読み取り専用 float.

**戻り値:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


フレームの中心の Y 座標を返します。読み取り専用 float.

**戻り値:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


フレームが水平方向に反転しているかどうかを判断します。読み取り専用 [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


フレームが垂直方向に反転しているかどうかを判断します。読み取り専用 [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```


フレームの座標を返します。読み取り専用 android.graphics.RectF.

**戻り値:**
android.graphics.RectF