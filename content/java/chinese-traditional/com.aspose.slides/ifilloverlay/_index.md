---
title: IFillOverlay
second_title: Aspose.Slides Java API 參考
description: 代表 Fill Overlay 效果。
type: docs
url: /zh-hant/com.aspose.slides/ifilloverlay/
---
**已實作的介面:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

代表 Fill Overlay 效果。Fill overlay 可用於為物件指定額外的 fill，並將兩個 fill 混合在一起。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. 讀/寫 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**返回值:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. 讀/寫 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. 唯讀 [IFillFormat](../../com.aspose.slides/ifillformat).

**返回值:**
[IFillFormat](../../com.aspose.slides/ifillformat)