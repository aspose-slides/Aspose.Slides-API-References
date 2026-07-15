---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /zh-hant/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

不可變的物件，包含有效的佈景主題屬性。

--------------------

此介面與 [ITheme](../../com.aspose.slides/itheme) 介面一起使用，以返回套用繼承的有效格式化值。

## Methods

| Method | Description |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | 返回顏色方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字型方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形狀格式方案。 |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


返回顏色方案。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**Returns:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


返回字型方案。 唯讀 [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)。

**Returns:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


返回形狀格式方案。 唯讀 [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)。

**Returns:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)