---
title: TextStyle
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Cette classe contient les propriétés de formatage du style de texte.
type: docs
url: /fr/com.aspose.slides/textstyle/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Cette classe contient les propriétés de formatage du style de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Si le niveau du style existe, le renvoie, sinon renvoie null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Propriétés de paragraphe par défaut. |
| [getEffective()](#getEffective--) | Obtient les données de formatage du style de texte effectif avec l'héritage appliqué. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Lecture seule : long.

**Renvoie :**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Si le niveau du style existe, le renvoie, sinon renvoie null.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice basé à zéro du niveau. Doit être compris dans l'intervalle 0..8. |

**Renvoie :**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Mise en forme du niveau [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Propriétés de paragraphe par défaut. Lecture seule [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Renvoie :**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Obtient les données de formatage du style de texte effectif avec l'héritage appliqué.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Un [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).