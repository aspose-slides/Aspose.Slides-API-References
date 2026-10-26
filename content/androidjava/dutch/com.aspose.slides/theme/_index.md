---
title: Theme
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een thema voor.
type: docs
url: /nl/com.aspose.slides/theme/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Stelt een thema voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Retourneert het kleurschema. |
| [getFontScheme()](#getFontScheme--) | Retourneert het lettertype-schema. |
| [getFormatScheme()](#getFormatScheme--) | Retourneert het vormopmaakschema. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie. |
| [getEffective()](#getEffective--) | Haalt effectieve themagegevens op met de erfenis toegepast. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Retourneert het kleurschema. Alleen-lezen [IColorScheme](../../com.aspose.slides/icolorscheme).

**Retourneert:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Retourneert het lettertype-schema. Alleen-lezen [IFontScheme](../../com.aspose.slides/ifontscheme).

**Retourneert:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Retourneert het vormopmaakschema. Alleen-lezen [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Retourneert:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Haalt effectieve themagegevens op met de erfenis toegepast.

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

**Retourneert:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - een [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Retourneert bovenliggend IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retourneert:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
long