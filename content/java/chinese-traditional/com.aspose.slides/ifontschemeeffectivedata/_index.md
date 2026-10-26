---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API 參考文件
description: 不可變的物件，包含有效的字型方案屬性。
type: docs
url: /zh-hant/com.aspose.slides/ifontschemeeffectivedata/
---
```
public interface IFontSchemeEffectiveData
```

不可變的物件，包含有效的字型方案屬性。

--------------------

此介面用作 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) 的一部分。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getMinor()](#getMinor--) | 傳回投影片「body」部分的字型集合。 |
| [getMajor()](#getMajor--) | 傳回投影片「heading」部分的字型集合。 |
| [getName()](#getName--) | 傳回字型方案名稱。 |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


傳回投影片「body」部分的字型集合。唯讀 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)。

**傳回:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


傳回投影片「heading」部分的字型集合。唯讀 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)。

**傳回:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


傳回字型方案名稱。唯讀 String。

**傳回:**
java.lang.String