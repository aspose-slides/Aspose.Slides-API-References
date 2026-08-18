---
title: TextStyle
second_title: Aspose.Slides Java API-referencia
description: Ez az osztály a szövegstílus formázási tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/textstyle/
---
**Öröklés:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**  
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner  
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Ez az osztály a szövegstílus formázási tulajdonságait tartalmazza.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Ha a stílus szintje létezik, visszaadja, különben null értéket ad vissza. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Alapértelmezett bekezdés tulajdonságai. |
| [getEffective()](#getEffective--) | Az öröklődés alkalmazásával kapja meg a hatékony szövegstílus formázási adatokat. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**  
long

### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

Ha a stílus szintje létezik, visszaadja, különben null értéket ad vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A szint nulla alapú indexe. 0..8 tartományban kell lennie. |

**Visszatér:**  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) – A(z) [IParagraphFormat](../../com.aspose.slides/iparagraphformat) szint formázása.

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

Alapértelmezett bekezdés tulajdonságai. Csak olvasható [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Visszatér:**  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

Az öröklődés alkalmazásával kapja meg a hatékony szövegstílus formázási adatokat.

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


**Visszatér:**  
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) – Egy [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).