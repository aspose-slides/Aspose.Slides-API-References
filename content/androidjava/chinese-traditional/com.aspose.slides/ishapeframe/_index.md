---
title: IShapeFrame
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示形狀框架的屬性。
type: docs
url: /zh-hant/com.aspose.slides/ishapeframe/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

表示形狀框架的屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getX()](#getX--) | 返回框架左上角的 X 座標。 |
| [getY()](#getY--) | 返回框架左上角的 Y 座標。 |
| [getWidth()](#getWidth--) | 返回框架的寬度。 |
| [getHeight()](#getHeight--) | 返回框架的高度。 |
| [getRotation()](#getRotation--) | 返回框架繞 Z 軸旋轉的角度（度）。 |
| [getCenterX()](#getCenterX--) | 返回框架中心的 X 座標。 |
| [getCenterY()](#getCenterY--) | 返回框架中心的 Y 座標。 |
| [getFlipH()](#getFlipH--) | 判斷框架是否水平翻轉。 |
| [getFlipV()](#getFlipV--) | 判斷框架是否垂直翻轉。 |
| [getRectangle()](#getRectangle--) | 返回框架的座標。 |
### getX() {#getX--}
```
public abstract float getX()
```

返回框架左上角的 X 座標。唯讀 float。

**返回：**
float
### getY() {#getY--}
```
public abstract float getY()
```

返回框架左上角的 Y 座標。唯讀 float。

**返回：**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

返回框架的寬度。唯讀 float。

**返回：**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

返回框架的高度。唯讀 float。

**返回：**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

返回框架繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉；負值表示逆時針旋轉。唯讀 float。

**返回：**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

返回框架中心的 X 座標。唯讀 float。

**返回：**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

返回框架中心的 Y 座標。唯讀 float。

**返回：**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

判斷框架是否水平翻轉。唯讀 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

判斷框架是否垂直翻轉。唯讀 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```

返回框架的座標。唯讀 android.graphics.RectF。

**返回：**
android.graphics.RectF