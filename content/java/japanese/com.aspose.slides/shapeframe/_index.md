---
title: ShapeFrame
second_title: Aspose.Slides for Java API リファレンス
description: シェイプフレームのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/shapeframe/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

シェイプフレームのプロパティを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | 新しいシェイプフレームのプロパティを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | フレームの左上隅の X 座標を返します。 |
| [getY()](#getY--) | フレームの左上隅の Y 座標を返します。 |
| [getWidth()](#getWidth--) | フレームの幅を返します。 |
| [getHeight()](#getHeight--) | フレームの高さを返します。 |
| [getRotation()](#getRotation--) | フレームが Z 軸周りに回転した角度（度）を返します。 |
| [getCenterX()](#getCenterX--) | フレームの中心の X 座標を返します。 |
| [getCenterY()](#getCenterY--) | フレームの中心の Y 座標を返します。 |
| [getFlipH()](#getFlipH--) | フレームが水平方向に反転しているかどうかを判定します。 |
| [getFlipV()](#getFlipV--) | フレームが垂直方向に反転しているかどうかを判定します。 |
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

新しいシェイプフレームのプロパティを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | フレームの X 座標です。 |
| y | float | フレームの Y 座標です。 |
| width | float | フレームの幅です。 |
| height | float | フレームの高さです。 |
| flipH | byte | フレームが水平方向に反転している場合は true。 |
| flipV | byte | フレームが垂直方向に反転している場合は true。 |
| rotationAngle | float | フレームが回転した角度（度）です。 |

### getX() {#getX--}
```
public final float getX()
```

フレームの左上隅の X 座標を返します。 読み取り専用 float。

**戻り値:**
float
### getY() {#getY--}
```
public final float getY()
```

フレームの左上隅の Y 座標を返します。 読み取り専用 float。

**戻り値:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

フレームの幅を返します。 読み取り専用 float。

**戻り値:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

フレームの高さを返します。 読み取り専用 float。

**戻り値:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

フレームが Z 軸周りに回転した角度（度）を返します。 正の値は時計回り、負の値は反時計回りを表します。 読み取り専用 float。

**戻り値:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

フレームの中心の X 座標を返します。 読み取り専用 float。

**戻り値:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

フレームの中心の Y 座標を返します。 読み取り専用 float。

**戻り値:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

フレームが水平方向に反転しているかどうかを判定します。 読み取り専用 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

フレームが垂直方向に反転しているかどうかを判定します。 読み取り専用 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

フレームの座標を返します。 読み取り専用 java.awt.geom.Rectangle2D.Float。

**戻り値:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

クローンを作成します

**戻り値:**
java.lang.Object - クローンされたシェイプフレーム。
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

クローンを作成します。

**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - クローンされたシェイプフレーム。
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するオブジェクトです。 |

**戻り値:**
boolean - **true** if obj is a ShapeFrame that has the same value as this instance; otherwise, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | このインスタンスと比較する ShapeFRameEx です。 |

**戻り値:**
boolean - **true** if value is a ShapeFrame that has the same value as this instance; otherwise, **false**.