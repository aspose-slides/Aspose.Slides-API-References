---
title: SlideUtil
second_title: Aspose.Slides för Android via Java API-referens
description: Erbjuder metoder som hjälper till att söka efter former och text i en presentation.
type: docs
url: /sv/com.aspose.slides/slideutil/
---
**Inheritance:**
java.lang.Object
```
public class SlideUtil
```

Erbjuder metoder som hjälper till att söka efter former och text i en presentation.
## Konstruktörer

| Constructor | Description |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Metoder

| Method | Description |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Hitta form efter alternativ text i en PPTX-presentation. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Hitta form efter alternativ text på en bild i en PPTX-presentation. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Söker efter alla former på den angivna bilden som matchar den givna platshållartypen. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Ändrar placeringen av alla former på bilden. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Ändrar placeringen av valda former på bilden. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Ändrar placeringen av alla former inom gruppformen. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Ändrar placeringen av valda former inom gruppformen. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Söker och ersätter text i presentationen med angivet format |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Söker och ersätter text i presentationen med angivet format |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Returnerar alla textramar på en bild i en PPTX-presentation. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Returnerar alla textramar på den angivna bilden som innehåller den givna texten. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Returnerar alla textramar i en PPTX-presentation. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Konverterar ett källfilformat till motsvarande [SaveFormat](../../com.aspose.slides/saveformat). |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Hitta form efter alternativ text i en PPTX-presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Skannad presentation. |
| altText | java.lang.String | Alternativ text för en form. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Shape eller null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Hitta form efter alternativ text på en bild i en PPTX-presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Skannad bild. |
| altText | java.lang.String | Alternativ text för en form. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Shape eller null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Söker efter alla former på den angivna bilden som matchar den givna platshållartypen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Bilden att söka efter former i. |
| placeholderType | byte | Typ av platshållare att filtrera former efter. |

**Returnerar:**
com.aspose.slides.IShape[] - En array av [IShape](../../com.aspose.slides/ishape)-objekt som matchar den angivna platshållartypen.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Ändrar placeringen av alla former på bilden. Justerar former till marginalerna eller bildens kant eller justerar dem relativt varandra.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | int | Bestämmer vilken typ av justering som ska tillämpas. |
| alignToSlide | boolean | Om true, kommer former att justeras relativt bildens kanter. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Föräldrabild. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Ändrar placeringen av valda former på bilden. Justerar former till marginalerna eller bildens kant eller justerar dem relativt varandra.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | int | Bestämmer vilken typ av justering som ska tillämpas. |
| alignToSlide | boolean | Om true, kommer former att justeras relativt bildens kanter. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Föräldrabild. |
| shapeIndexes | int[] | Index för former som ska justeras. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Ändrar placeringen av alla former inom gruppformen. Justerar former till marginalerna eller bildens kant eller justerar dem relativt varandra.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | int | Bestämmer vilken typ av justering som ska tillämpas. |
| alignToSlide | boolean | Om true, kommer former att justeras relativt bildens kanter. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Föräldragruppform. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Ändrar placeringen av valda former inom gruppformen. Justerar former till marginalerna eller bildens kant eller justerar dem relativt varandra.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | int | Bestämmer vilken typ av justering som ska tillämpas. |
| alignToSlide | boolean | Om true, kommer former att justeras relativt bildens kanter. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Föräldragruppform. |
| shapeIndexes | int[] | Index för former som ska justeras. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Söker och ersätter text i presentationen med angivet format

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Skannad presentation. |
| withMasters | boolean | Bestämmer om masterbilder ska genomsökas. |
| find | java.lang.String | Strängvärde att hitta. |
| replace | java.lang.String | Strängvärde att ersätta. tecken i den hittade strängen |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Söker och ersätter text i presentationen med angivet format

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Skannad presentation. |
| withMasters | boolean | Bestämmer om masterbilder ska genomsökas. |
| find | java.lang.String | Strängvärde att hitta. |
| replace | java.lang.String | Strängvärde att ersätta. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format för att ersätta textdel. Om null används formatet för det första tecknet i den hittade strängen |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Returnerar alla textramar på en bild i en PPTX-presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Skannad bild. |

**Returnerar:**
com.aspose.slides.ITextFrame[] - Array av [TextFrame](../../com.aspose.slides/textframe)-objekt.
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Returnerar alla textramar på den angivna bilden som innehåller den givna texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Bilden att söka. |
| text | java.lang.String | Texten att söka efter i textramar. |
| checkPlaceholderText | boolean | Anger om tomma textramar vars platshållartext innehåller söktexten ska inkluderas. |

**Returnerar:**
com.aspose.slides.ITextFrame[] - En array av [ITextFrame](../../com.aspose.slides/itextframe)-objekt som innehåller den angivna texten.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Returnerar alla textramar i en PPTX-presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Skannad presentation. |
| withMasters | boolean | Bestämmer om masterbilder ska genomsökas. |

**Returnerar:**
com.aspose.slides.ITextFrame[] - Array av [TextFrame](../../com.aspose.slides/textframe)-objekt.
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Konverterar ett källfilformat till motsvarande [SaveFormat](../../com.aspose.slides/saveformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | int | Källfilformatet. |

**Returnerar:**
int - Det motsvarande [SaveFormat](../../com.aspose.slides/saveformat)-värdet.