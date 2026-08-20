---
title: IGlow
second_title: Aspose.Slides for Java API 參考文件
description: 代表一種 Glow 效果，會在物件邊緣外側加入顏色模糊輪廓。
type: docs
url: /zh-hant/com.aspose.slides/iglow/
---
**所有已實作介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

代表一種 Glow 效果，會在物件邊緣外側加入顏色模糊輪廓。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRadius()](#getRadius--) | 半徑。 |
| [setRadius(double value)](#setRadius-double-) | 半徑。 |
| [getColor()](#getColor--) | 顏色格式。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

半徑。可讀寫 double。

**返回：**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

半徑。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

顏色格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)