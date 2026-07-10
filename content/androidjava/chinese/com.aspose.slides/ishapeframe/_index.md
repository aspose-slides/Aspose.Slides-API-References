---
title: IShapeFrame
second_title: Aspose.Slides for Android Java API 参考
description: 表示形状框的属性。
type: docs
url: /zh/com.aspose.slides/ishapeframe/
---
**所有实现的接口：**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

表示形状框的属性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 返回框左上角的 X 坐标。 |
| [getY()](#getY--) | 返回框左上角的 Y 坐标。 |
| [getWidth()](#getWidth--) | 返回框的宽度。 |
| [getHeight()](#getHeight--) | 返回框的高度。 |
| [getRotation()](#getRotation--) | 返回框绕 Z 轴旋转的角度（度）。 |
| [getCenterX()](#getCenterX--) | 返回框中心的 X 坐标。 |
| [getCenterY()](#getCenterY--) | 返回框中心的 Y 坐标。 |
| [getFlipH()](#getFlipH--) | 确定框是否水平翻转。 |
| [getFlipV()](#getFlipV--) | 确定框是否垂直翻转。 |
| [getRectangle()](#getRectangle--) | 返回框的坐标。 |

### getX() {#getX--}
```
public abstract float getX()
```

返回框左上角的 X 坐标。只读 float。

**返回:**  
float

### getY() {#getY--}
```
public abstract float getY()
```

返回框左上角的 Y 坐标。只读 float。

**返回:**  
float

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

返回框的宽度。只读 float。

**返回:**  
float

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

返回框的高度。只读 float。

**返回:**  
float

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

返回框绕 Z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。只读 float。

**返回:**  
float

### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

返回框中心的 X 坐标。只读 float。

**返回:**  
float

### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

返回框中心的 Y 坐标。只读 float。

**返回:**  
float

### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

确定框是否水平翻转。只读 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

确定框是否垂直翻转。只读 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```

返回框的坐标。只读 android.graphics.RectF。

**返回:**  
android.graphics.RectF