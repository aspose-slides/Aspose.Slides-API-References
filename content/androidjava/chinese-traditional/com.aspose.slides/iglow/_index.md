---
title: IGlow
second_title: Aspose.Slides for Android via Java API 參考文件
description: 代表一種發光效果，會在物件的邊緣之外加入顏色模糊的輪廓。
type: docs
url: /zh-hant/com.aspose.slides/iglow/
---
**所有實作介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

代表一種發光效果，會在物件的邊緣之外加入顏色模糊的輪廓。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Radius. 可讀寫 double.

**返回：**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Radius. 可讀寫 double.

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Color format. 唯讀 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)