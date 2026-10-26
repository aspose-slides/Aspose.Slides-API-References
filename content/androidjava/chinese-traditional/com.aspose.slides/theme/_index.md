---
title: Theme
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表一個主題。
type: docs
url: /zh-hant/com.aspose.slides/theme/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

表示一個主題。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 返回色彩方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字體方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回圖形格式方案。 |
| [getPresentation()](#getPresentation--) | 返回父簡報。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效主題資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

返回色彩方案。唯讀 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**返回：**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

返回字體方案。唯讀 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**返回：**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

返回圖形格式方案。唯讀 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**返回：**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

取得套用繼承後的有效主題資料。

--------------------

> ```
> This example demonstrates getting effective theme properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IThemeEffectiveData effectiveTheme  = pres.getSlides().get_Item(0).getThemeManager().getOverrideTheme().getEffective();
>  	System.out.println("Font scheme name: " + effectiveTheme.getFontScheme().getName());
>  	System.out.println("Major latin font: " + effectiveTheme.getFontScheme().getMajor().getLatinFont().getFontName());
>  	System.out.println("Minor latin font: " + effectiveTheme.getFontScheme().getMinor().getLatinFont().getFontName());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - 一個 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回 parent IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

版本。唯讀 long。

**返回：**
long