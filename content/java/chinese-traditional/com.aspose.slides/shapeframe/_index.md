---
title: ShapeFrame
second_title: Aspose.Slides for Java API 參考
description: 表示形狀框架的屬性。
type: docs
url: /zh-hant/com.aspose.slides/shapeframe/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

表示形狀框架的屬性。
## 建構函式

| 建構子 | 說明 |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | 建立新的形狀框架屬性。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getX()](#getX--) | 傳回框架左上角的 X 坐標。 |
| [getY()](#getY--) | 傳回框架左上角的 Y 坐標。 |
| [getWidth()](#getWidth--) | 傳回框架的寬度。 |
| [getHeight()](#getHeight--) | 傳回框架的高度。 |
| [getRotation()](#getRotation--) | 傳回框架繞 Z 軸旋轉的角度（度）。 |
| [getCenterX()](#getCenterX--) | 傳回框架中心的 X 坐標。 |
| [getCenterY()](#getCenterY--) | 傳回框架中心的 Y 坐標。 |
| [getFlipH()](#getFlipH--) | 判斷框架是否水平翻轉。 |
| [getFlipV()](#getFlipV--) | 判斷框架是否垂直翻轉。 |
| [getRectangle()](#getRectangle--) | 傳回框架的座標。 |
| [deepClone()](#deepClone--) | 複製 |
| [cloneT()](#cloneT--) | 複製。 |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 傳回一個值，用以指示此實例是否等於指定的物件。 |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | 傳回一個值，用以指示此實例是否等於指定的物件。 |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

建立新的形狀框架屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 框架的 X 坐標。 |
| y | float | 框架的 Y 坐標。 |
| width | float | 框架的寬度。 |
| height | float | 框架的高度。 |
| flipH | byte | 若框架水平翻轉則為 True。 |
| flipV | byte | 若框架垂直翻轉則為 True。 |
| rotationAngle | float | 框架旋轉的角度（度）。 |

### getX() {#getX--}
```
public final float getX()
```

傳回框架左上角的 X 坐標。唯讀 float。

**傳回值:**
float
### getY() {#getY--}
```
public final float getY()
```

傳回框架左上角的 Y 坐標。唯讀 float。

**傳回值:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

傳回框架的寬度。唯讀 float。

**傳回值:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

傳回框架的高度。唯讀 float。

**傳回值:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

傳回框架繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉；負值表示逆時針旋轉。唯讀 float。

**傳回值:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

傳回框架中心的 X 坐標。唯讀 float。

**傳回值:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

傳回框架中心的 Y 坐標。唯讀 float。

**傳回值:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

判斷框架是否水平翻轉。唯讀 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回值:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

判斷框架是否垂直翻轉。唯讀 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回值:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

傳回框架的座標。唯讀 java.awt.geom.Rectangle2D.Float。

**傳回值:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

複製

**傳回值:**
java.lang.Object - 已複製的形狀框架。
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

複製。

**傳回值:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - 已複製的形狀框架。
### hashCode() {#hashCode--}
```
public int hashCode()
```



**傳回值:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

傳回一個值，用以指示此實例是否等於指定的物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要與此實例比較的物件。 |

**傳回值:**
boolean - **true** 若 obj 為與此實例具有相同值的 ShapeFrame；否則為 **false**。
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

傳回一個值，用以指示此實例是否等於指定的物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | 要與此實例比較的 ShapeFRameEx。 |

**傳回值:**
boolean - **true** 若 value 為與此實例具有相同值的 ShapeFrame；否則為 **false**.