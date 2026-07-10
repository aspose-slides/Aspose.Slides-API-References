---
title: IBackgroundEffectiveData
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 不可变对象，包含有效的背景属性。
type: docs
url: /zh/com.aspose.slides/ibackgroundeffectivedata/
---
**所有已实现的接口：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

不可变对象，它包含有效的背景属性。

--------------------

此接口与 [IBackground](../../com.aspose.slides/ibackground) 接口一起使用，以返回已应用继承的有效格式化值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 返回有效的填充格式。 |
| [getEffectFormat()](#getEffectFormat--) | 返回有效的效果格式。 |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


返回有效的填充格式。只读 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**返回：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


返回有效的效果格式。只读 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**返回：**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)