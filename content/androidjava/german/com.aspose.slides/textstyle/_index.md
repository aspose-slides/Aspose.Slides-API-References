---
title: TextStyle
second_title: Aspose.Slides für Android über die Java API Referenz
description: Diese Klasse enthält die Formatierungseigenschaften des Textstils.
type: docs
url: /de/com.aspose.slides/textstyle/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Diese Klasse enthält die Formatierungseigenschaften des Textstils.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) | |
| [getLevel(int index)](#getLevel-int-) | Wenn das Stilniveau existiert, wird es zurückgegeben, andernfalls wird null zurückgegeben. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standardabsatz-Eigenschaften. |
| [getEffective()](#getEffective--) | Ermittelt effektive Textstildaten mit angewandter Vererbung. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesbar long.

**Rückgabe:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Wenn das Stilniveau existiert, wird es zurückgegeben, andernfalls wird null zurückgegeben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Nullbasierter Index des Levels. Muss im Intervall 0..8 liegen. |

**Rückgabe:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatierung von Ebene [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Standardabsatz-Eigenschaften. Nur lesbar [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Rückgabe:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Ermittelt effektive Textstildaten mit angewandter Vererbung.

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


**Rückgabe:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Ein [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).