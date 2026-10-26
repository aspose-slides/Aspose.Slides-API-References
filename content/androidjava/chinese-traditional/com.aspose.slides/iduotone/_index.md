---
title: IDuotone
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示雙色調效果。
type: docs
url: /zh-hant/com.aspose.slides/iduotone/
---
**所有已實作的介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IDuotone extends IImageTransformOperation, IAccessiblePVIObject<IDuotoneEffectiveData>
```

表示雙色調效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor1()](#getColor1--) | 傳回深色像素的目標顏色格式。 |
| [getColor2()](#getColor2--) | 傳回淺色像素的目標顏色格式。 |
### getColor1() {#getColor1--}
```
public abstract IColorFormat getColor1()
```


傳回深色像素的目標顏色格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat).

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public abstract IColorFormat getColor2()
```


傳回淺色像素的目標顏色格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat).

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)