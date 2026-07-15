---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 不可變的物件，包含有效的字型配置屬性。
type: docs
url: /zh-hant/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

不可變的物件，包含有效的字型配置屬性。

--------------------

此介面作為 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) 的一部分使用。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getMinor()](#getMinor--) | 返回投影片「正文」部分的字型集合。 |
| [getMajor()](#getMajor--) | 返回投影片「標題」部分的字型集合。 |
| [getName()](#getName--) | 返回字型方案名稱。 |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

返回投影片「正文」部分的字型集合。唯讀 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)。

**返回：**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

返回投影片「標題」部分的字型集合。唯讀 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)。

**返回：**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

返回字型方案名稱。唯讀 String。

**返回：**
java.lang.String