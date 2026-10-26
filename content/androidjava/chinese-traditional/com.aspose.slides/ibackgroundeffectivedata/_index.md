---
title: IBackgroundEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變動的物件，包含有效的背景屬性。
type: docs
url: /zh-hant/com.aspose.slides/ibackgroundeffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

不可變動的物件，包含有效的背景屬性。

--------------------

此介面與 [IBackground](../../com.aspose.slides/ibackground) 介面一起使用，以在套用繼承後返回有效的格式化值。

## Methods

| 方法 | 描述 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 返回有效的填滿格式。 |
| [getEffectFormat()](#getEffectFormat--) | 返回有效的效果格式。 |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


返回有效的填滿格式。唯讀 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**返回：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


返回有效的效果格式。唯讀 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**返回：**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)