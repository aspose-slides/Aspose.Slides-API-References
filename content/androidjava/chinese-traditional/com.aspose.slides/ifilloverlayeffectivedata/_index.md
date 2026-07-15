---
title: IFillOverlayEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變的物件，表示 Fill Overlay 效果。
type: docs
url: /zh-hant/com.aspose.slides/ifilloverlayeffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IFillOverlayEffectiveData extends IEffectEffectiveData
```

不可變的物件，表示 Fill Overlay 效果。Fill overlay 可用於為物件指定額外的填充，並將兩個填充混合在一起。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | 填充格式。 |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. 唯讀 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**返回值：**
int
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


填充格式。唯讀 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**返回值：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)