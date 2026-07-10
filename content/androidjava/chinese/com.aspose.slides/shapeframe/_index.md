---
title: ShapeFrame
second_title: Aspose.Slides for Android via Java API 参考
description: 表示形状框的属性。
type: docs
url: /zh/com.aspose.slides/shapeframe/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

表示形状框的属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | 创建新的形状框属性。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 返回框左上角的 X 坐标。 |
| [getY()](#getY--) | 返回框左上角的 Y 坐标。 |
| [getWidth()](#getWidth--) | 返回框的宽度。 |
| [getHeight()](#getHeight--) | 返回框的高度。 |
| [getRotation()](#getRotation--) | 返回框绕 Z 轴旋转的角度（度数）。 |
| [getCenterX()](#getCenterX--) | 返回框中心的 X 坐标。 |
| [getCenterY()](#getCenterY--) | 返回框中心的 Y 坐标。 |
| [getFlipH()](#getFlipH--) | 确定框是否水平翻转。 |
| [getFlipV()](#getFlipV--) | 确定框是否垂直翻转。 |
| [getRectangle()](#getRectangle--) | 返回框的坐标。 |
| [deepClone()](#deepClone--) | 克隆 |
| [cloneT()](#cloneT--) | 克隆。 |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的对象。 |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | 返回一个值，指示此实例是否等于指定的对象。 |

### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


创建新的形状框属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 框的 X 坐标。 |
| y | float | 框的 Y 坐标。 |
| width | float | 框的宽度。 |
| height | float | 框的高度。 |
| flipH | byte | 如果框水平翻转则为 true。 |
| flipV | byte | 如果框垂直翻转则为 true。 |
| rotationAngle | float | 框旋转的角度（度数）。 |

### getX() {#getX--}
```
public final float getX()
```


返回框左上角的 X 坐标。只读 float。

**返回值：**
float

### getY() {#getY--}
```
public final float getY()
```


返回框左上角的 Y 坐标。只读 float。

**返回值：**
float

### getWidth() {#getWidth--}
```
public final float getWidth()
```


返回框的宽度。只读 float。

**返回值：**
float

### getHeight() {#getHeight--}
```
public final float getHeight()
```


返回框的高度。只读 float。

**返回值：**
float

### getRotation() {#getRotation--}
```
public final float getRotation()
```


返回框绕 Z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。只读 float。

**返回值：**
float

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


返回框中心的 X 坐标。只读 float。

**返回值：**
float

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


返回框中心的 Y 坐标。只读 float。

**返回值：**
float

### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


确定框是否水平翻转。只读 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回值：**
byte

### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


确定框是否垂直翻转。只读 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回值：**
byte

### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


返回框的坐标。只读 android.graphics.RectF。

**返回值：**
android.graphics.RectF

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


克隆

**返回值：**
java.lang.Object - 克隆的形状框。

### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


克隆。

**返回值：**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - 克隆的形状框。

### hashCode() {#hashCode--}
```
public int hashCode()
```




**返回值：**
int

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的对象。 |

**返回值：**
boolean - **true** 表示 obj 是与此实例具有相同值的 ShapeFrame；否则 **false**。

### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


返回一个值，指示此实例是否等于指定的对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | 用于与此实例比较的 ShapeFRameEx。 |

**返回值：**
boolean - **true** 表示 value 是与此实例具有相同值的 ShapeFrame；否则 **false**。