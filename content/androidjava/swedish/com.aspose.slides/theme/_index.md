---
title: Theme
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett tema.
type: docs
url: /sv/com.aspose.slides/theme/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Representerar ett tema.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Returnerar färgschemat. |
| [getFontScheme()](#getFontScheme--) | Returnerar typsnittsschemat. |
| [getFormatScheme()](#getFormatScheme--) | Returnerar formatmall för former. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen. |
| [getEffective()](#getEffective--) | Hämtar effektiv temadata med ärvning tillämpad. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Returnerar färgschemat. Skrivskyddad [IColorScheme](../../com.aspose.slides/icolorscheme).

**Returnerar:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Returnerar typsnittsschemat. Skrivskyddad [IFontScheme](../../com.aspose.slides/ifontscheme).

**Returnerar:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Returnerar formatmall för former. Skrivskyddad [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Returnerar:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Hämtar effektiv temadata med ärvning tillämpad.

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


**Returnerar:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - en [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Returnerar förälder IPresentationComponent. Skrivskyddad [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long