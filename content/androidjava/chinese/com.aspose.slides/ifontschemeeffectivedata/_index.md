---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API 参考
description: 不可变对象，其中包含有效字体方案属性。
type: docs
url: /zh/com.aspose.slides/ifontschemeeffectivedata/
---
```
public interface IFontSchemeEffectiveData
```

不可变对象，其中包含有效字体方案属性。

--------------------

此接口作为 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) 的一部分使用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMinor()](#getMinor--) | 返回幻灯片 "body" 部分的字体集合。 |
| [getMajor()](#getMajor--) | 返回幻灯片 "heading" 部分的字体集合。 |
| [getName()](#getName--) | 返回字体方案名称。 |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

返回幻灯片 "body" 部分的字体集合。只读 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)。

**返回:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

返回幻灯片 "heading" 部分的字体集合。只读 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)。

**返回:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

返回字体方案名称。只读 String。

**返回:**
java.lang.String