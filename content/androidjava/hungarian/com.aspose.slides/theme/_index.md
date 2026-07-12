---
title: Theme
second_title: Aspose.Slides for Android a Java API hivatkozásán keresztül
description: Egy témát képvisel.
type: docs
url: /hu/com.aspose.slides/theme/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Egy témát képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Visszaadja a színsémát. |
| [getFontScheme()](#getFontScheme--) | Visszaadja a betűkészlet sémát. |
| [getFormatScheme()](#getFormatScheme--) | Visszaadja az alakzatformátum sémát. |
| [getPresentation()](#getPresentation--) | Visszaadja a szülő prezentációt. |
| [getEffective()](#getEffective--) | Lekéri a hatékony témadatokat az öröklődés alkalmazásával. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Visszaadja a színsémát. Csak olvasható [IColorScheme](../../com.aspose.slides/icolorscheme).

**Visszatér:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Visszaadja a betűkészlet sémát. Csak olvasható [IFontScheme](../../com.aspose.slides/ifontscheme).

**Visszatér:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Visszaadja az alakzatformátum sémát. Csak olvasható [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Visszatér:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a szülő prezentációt. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Lekéri a hatékony témadatokat az öröklődés alkalmazásával.

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


**Visszatér:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Visszaadja a szülő IPresentationComponent-et. Csak olvasható [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatér:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long