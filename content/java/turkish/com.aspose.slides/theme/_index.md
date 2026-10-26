---
title: Theme
second_title: Aspose.Slides for Java API Referansı
description: Bir temayı temsil eder.
type: docs
url: /tr/com.aspose.slides/theme/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Bir temayı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Renk şemasını döndürür. |
| [getFontScheme()](#getFontScheme--) | Yazı tipi şemasını döndürür. |
| [getFormatScheme()](#getFormatScheme--) | Şekil formatı şemasını döndürür. |
| [getPresentation()](#getPresentation--) | Üst sunumu döndürür. |
| [getEffective()](#getEffective--) | Miras uygulanmış etkili tema verilerini alır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Renk şemasını döndürür. Sadece okunabilir [IColorScheme](../../com.aspose.slides/icolorscheme).

**Döndürür:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Yazı tipi şemasını döndürür. Sadece okunabilir [IFontScheme](../../com.aspose.slides/ifontscheme).

**Döndürür:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Şekil formatı şemasını döndürür. Sadece okunabilir [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Döndürür:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Üst sunumu döndürür. Sadece okunabilir [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Miras uygulanmış etkili tema verilerini alır.

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

**Döndürür:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Bir [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Sadece okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent nesnesini döndürür. Sadece okunabilir [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Sürüm. Sadece okunabilir long.

**Döndürür:**
long