---
title: ShapeFrame
second_title: Aspose.Slides for Android の Java API リファレンス
description: 形状フレームのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/shapeframe/
---
**継承:**
java.lang.Object

**実装済みインターフェイス:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

形状フレームのプロパティを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | 新しい形状フレームのプロパティを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | フレームの左上隅のX座標を返します。 |
| [getY()](#getY--) | フレームの左上隅のY座標を返します。 |
| [getWidth()](#getWidth--) | フレームの幅を返します。 |
| [getHeight()](#getHeight--) | フレームの高さを返します。 |
| [getRotation()](#getRotation--) | フレームがZ軸周りに回転した角度（度）を返します。 |
| [getCenterX()](#getCenterX--) | フレームの中心のX座標を返します。 |
| [getCenterY()](#getCenterY--) | フレームの中心のY座標を返します。 |
| [getFlipH()](#getFlipH--) | フレームが水平に反転しているかどうかを判定します。 |
| [getFlipV()](#getFlipV--) | フレームが垂直に反転しているかどうかを判定します。 |
| [getRectangle()](#getRectangle--) | フレームの座標を返します。 |
| [deepClone()](#deepClone--) | クローンを作成します |
| [cloneT()](#cloneT--) | クローンを作成します。 |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。 |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。 |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

新しい形状フレームのプロパティを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | フレームのX座標。 |
| y | float | フレームのY座標。 |
| width | float | フレームの幅。 |
| height | float | フレームの高さ。 |
| flipH | byte | フレームが水平に反転している場合は true。 |
| flipV | byte | フレームが垂直に反転している場合は true。 |
| rotationAngle | float | フレームが回転した角度（度）。 |
### getX() {#getX--}
```
public final float getX()
```

フレームの左上隅のX座標を返します。読み取り専用 float。

**戻り値:**
float
### getY() {#getY--}
```
public final float getY()
```

フレームの左上隅のY座標を返します。読み取り専用 float。

**戻り値:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

フレームの幅を返します。読み取り専用 float。

**戻り値:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

フレームの高さを返します。読み取り専用 float。

**戻り値:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

フレームがZ軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り専用 float。

**戻り値:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

フレームの中心のX座標を返します。読み取り専用 float。

**戻り値:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

フレームの中心のY座標を返します。読み取り専用 float。

**戻り値:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

フレームが水平に反転しているかどうかを判定します。読み取り専用 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

フレームが垂直に反転しているかどうかを判定します。読み取り専用 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

フレームの座標を返します。読み取り専用 android.graphics.RectF。

**戻り値:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

クローンを作成します

**戻り値:**
java.lang.Object - クローン化された形状フレーム。
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

クローンを作成します。

**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - クローン化された形状フレーム。
### hashCode() {#hashCode--}
```
public int hashCode()
```




**戻り値:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するオブジェクト。 |

**戻り値:**
boolean - **true** は、obj がこのインスタンスと同じ値を持つ ShapeFrame の場合; それ以外の場合は **false**。
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | このインスタンスと比較する ShapeFRameEx。 |

**戻り値:**
boolean - **true** は、value がこのインスタンスと同じ値を持つ ShapeFrame の場合; それ以外の場合は **false**。