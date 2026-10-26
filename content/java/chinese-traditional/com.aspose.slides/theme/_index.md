---
title: Theme
second_title: Aspose.Slides for Java API 參考
description: 表示一個主題。
type: docs
url: /zh-hant/com.aspose.slides/theme/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

表示一個主題。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 傳回顏色配置。 |
| [getFontScheme()](#getFontScheme--) | 傳回字型配置。 |
| [getFormatScheme()](#getFormatScheme--) | 傳回形狀格式配置。 |
| [getPresentation()](#getPresentation--) | 傳回父簡報。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效主題資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


傳回顏色配置。唯讀 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**傳回:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


傳回字型配置。唯讀 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**傳回:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


傳回形狀格式配置。唯讀 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**傳回:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


傳回父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```


取得套用繼承後的有效主題資料。

--------------------

> ```
> 此範例示範取得有效的主題屬性。
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


**傳回:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - 一個 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


傳回 parent IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**傳回:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```


版本。唯讀 long。

**傳回:**
long