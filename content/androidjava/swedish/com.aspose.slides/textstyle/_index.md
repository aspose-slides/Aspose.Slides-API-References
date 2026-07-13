---
title: TextStyle
second_title: Aspose.Slides för Android via Java API-referens
description: Denna klass innehåller egenskaperna för textstilsformatering.
type: docs
url: /sv/com.aspose.slides/textstyle/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Denna klass innehåller egenskaperna för textstilsformatering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Om nivå av stil finns returneras den, annars returneras null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standardparagrafens egenskaper. |
| [getEffective()](#getEffective--) | Hämtar effektiv textstilsformateringsdata med arv tillämpat. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Endast läsbar long.

**Returnerar:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

Om nivå av stil finns returneras den, annars returneras null.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för nivå. Måste ligga i intervallet 0..8. |

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatering av nivå [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

Standardparagrafens egenskaper. Endast läsbar [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

Hämtar effektiv textstilsformateringsdata med arv tillämpat.

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


**Returnerar:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - en [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).