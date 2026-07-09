---
title: Theme
second_title: Référence API Java d'Aspose.Slides pour Android
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
| [getColorScheme()](#getColorScheme--) | Renvoie le jeu de couleurs. |
| [getFontScheme()](#getFontScheme--) | Renvoie le jeu de polices. |
| [getFormatScheme()](#getFormatScheme--) | Renvoie le jeu de format de forme. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente. |
| [getEffective()](#getEffective--) | Obtient les données effectives du thème avec l’héritage appliqué. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Renvoie le jeu de couleurs. Lecture seule [IColorScheme](../../com.aspose.slides/icolorscheme).

**Renvoie:**  
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Renvoie le jeu de polices. Lecture seule [IFontScheme](../../com.aspose.slides/ifontscheme).

**Renvoie:**  
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Renvoie le jeu de format de forme. Lecture seule [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Renvoie:**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parente. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Obtient les données effectives du thème avec l’héritage appliqué.

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

**Returns:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Renvoie le IPresentationComponent parent. Lecture seule [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Renvoie:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()

Version. Read-only long.

**Renvoie:**
long