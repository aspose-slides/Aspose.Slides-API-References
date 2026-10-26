---
title: ITheme
second_title: Aspose.Slides for Java API 參考文件
description: 表示一個主題。
type: docs
url: /zh-hant/com.aspose.slides/itheme/
---
**所有已實作的介面：**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

表示一個主題。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 傳回色彩配置。 |
| [getFontScheme()](#getFontScheme--) | 傳回字型配置。 |
| [getFormatScheme()](#getFormatScheme--) | 傳回形狀格式配置。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效主題資料。 |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

傳回色彩配置。唯讀 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**傳回：**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

傳回字型配置。唯讀 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**傳回：**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

傳回形狀格式配置。唯讀 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**傳回：**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

取得套用繼承後的有效主題資料。

**傳回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - 一個 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).