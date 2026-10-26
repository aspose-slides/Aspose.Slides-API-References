---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API 參考文件
description: 不可變的物件，包含有效的佈景主題屬性。
type: docs
url: /zh-hant/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

不可變的物件，包含有效的佈景主題屬性。

--------------------

此介面與 [ITheme](../../com.aspose.slides/itheme) 介面一起使用，以返回套用繼承的有效格式化值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | 傳回色彩配置方案。 |
| [getFontScheme()](#getFontScheme--) | 傳回字型配置方案。 |
| [getFormatScheme()](#getFormatScheme--) | 傳回圖形格式配置方案。 |

### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

傳回色彩配置方案。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**回傳:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - 色彩配置方案 [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

傳回字型配置方案。唯讀 [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)。

**回傳:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

傳回圖形格式配置方案。唯讀 [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)。

**回傳:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)