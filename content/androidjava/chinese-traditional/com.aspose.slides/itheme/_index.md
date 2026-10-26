---
title: ITheme
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示一個主題。
type: docs
url: /zh-hant/com.aspose.slides/itheme/
---
**所有實作的介面：**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

表示一個主題。
## 方法

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 返回顏色方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字型方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形狀格式方案。 |
| [getEffective()](#getEffective--) | 獲取套用繼承的有效主題資料。 |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


返回顏色方案。唯讀 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**返回：**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


返回字型方案。唯讀 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**返回：**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


返回形狀格式方案。唯讀 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**返回：**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


獲取套用繼承的有效主題資料。

**返回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - 一個 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)。