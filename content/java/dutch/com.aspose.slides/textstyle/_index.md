---
title: TextStyle
second_title: Aspose.Slides voor Java API-referentie
description: Deze klasse bevat de tekststijl-opmaak eigenschappen.
type: docs
url: /nl/com.aspose.slides/textstyle/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Deze klasse bevat de tekststijl-opmaak eigenschappen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Als het niveau van de stijl bestaat, retourneert het, anders retourneert het null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standaard alinea-eigenschappen. |
| [getEffective()](#getEffective--) | Haalt effectieve tekststijl-opmaakgegevens op met de toegepaste overerving. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Als het niveau van de stijl bestaat, retourneert het, anders retourneert het null.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Nulgebaseerde index van niveau. Moet liggen in interval 0..8. |

**Retour:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) – Opmaak van niveau [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Standaard alinea-eigenschappen. Alleen-lezen [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retour:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Haalt effectieve tekststijl-opmaakgegevens op met de toegepaste overerving.

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


**Retour:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) – Een [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).