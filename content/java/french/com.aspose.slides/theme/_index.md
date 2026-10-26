---
title: Theme
second_title: Référence API Aspose.Slides pour Java
description: Représente un thème.
type: docs
url: /fr/com.aspose.slides/theme/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Représente un thème.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Retourne le jeu de couleurs. |
| [getFontScheme()](#getFontScheme--) | Retourne le jeu de polices. |
| [getFormatScheme()](#getFormatScheme--) | Retourne le jeu de formats de forme. |
| [getPresentation()](#getPresentation--) | Retourne la présentation parente. |
| [getEffective()](#getEffective--) | Obtient les données de thème effectives avec l'héritage appliqué. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Retourne le jeu de couleurs. Lecture seule [IColorScheme](../../com.aspose.slides/icolorscheme).

**Retourne:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Retourne le jeu de polices. Lecture seule [IFontScheme](../../com.aspose.slides/ifontscheme).

**Retourne:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Retourne le jeu de formats de forme. Lecture seule [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Retourne:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourne la présentation parente. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Retourne:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Obtient les données de thème effectives avec l'héritage appliqué.

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

**Retourne:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Un [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourne l'objet Parent_Immediate. Lecture seule IDOMObject.

**Retourne:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Retourne le composant parent IPresentationComponent. Lecture seule [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retourne:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Version. Lecture seule long.

**Retourne:**
long