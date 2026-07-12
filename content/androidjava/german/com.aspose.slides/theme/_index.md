---
title: Theme
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt ein Thema dar.
type: docs
url: /de/com.aspose.slides/theme/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Stellt ein Thema dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Gibt das Farbschema zurück. |
| [getFontScheme()](#getFontScheme--) | Gibt das Schriftartschema zurück. |
| [getFormatScheme()](#getFormatScheme--) | Gibt das Shape-Format-Schema zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation zurück. |
| [getEffective()](#getEffective--) | Ruft effektive Themendaten mit angewandter Vererbung ab. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Gibt das Farbschema zurück. Nur lesbar [IColorScheme](../../com.aspose.slides/icolorscheme).

**Rückgabewert:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Gibt das Schriftartschema zurück. Nur lesbar [IFontScheme](../../com.aspose.slides/ifontscheme).

**Rückgabewert:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Gibt das Shape-Format-Schema zurück. Nur lesbar [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Rückgabewert:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Ruft effektive Themendaten mit angewandter Vererbung ab.

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

**Rückgabewert:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Ein [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Gibt das übergeordnete IPresentationComponent zurück. Nur lesbar [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabewert:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Version. Nur lesbar long.

**Rückgabewert:**
long