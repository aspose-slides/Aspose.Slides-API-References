---
title: Theme
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje motiv.
type: docs
url: /cs/com.aspose.slides/theme/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Představuje motiv.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Vrací barevné schéma. |
| [getFontScheme()](#getFontScheme--) | Vrací schéma písem. |
| [getFormatScheme()](#getFormatScheme--) | Vrací schéma formátu tvarů. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci. |
| [getEffective()](#getEffective--) | Získá efektivní data motivu s aplikovaným děděním. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Vrací barevné schéma. Pouze pro čtení [IColorScheme](../../com.aspose.slides/icolorscheme).

**Vrací:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Vrací schéma písem. Pouze pro čtení [IFontScheme](../../com.aspose.slides/ifontscheme).

**Vrací:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Vrací schéma formátu tvarů. Pouze pro čtení [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Vrací:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Vrací nadřazenou prezentaci. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```


Získá efektivní data motivu s aplikovaným děděním.

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


**Vrací:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Jedná se o [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Vrací nadřazený IPresentationComponent. Pouze pro čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```


Verze. Pouze pro čtení long.

**Vrací:**
long