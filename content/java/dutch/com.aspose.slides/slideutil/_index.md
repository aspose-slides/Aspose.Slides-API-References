---
title: SlideUtil
second_title: Aspose.Slides voor Java API-referentie
description: Biedt methoden die helpen bij het zoeken naar vormen en tekst in een presentatie.
type: docs
url: /nl/com.aspose.slides/slideutil/
---
**Erfenis:**
java.lang.Object
```
public class SlideUtil
```

Biedt methoden die helpen bij het zoeken naar vormen en tekst in een presentatie.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Methoden

| Method | Beschrijving |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Zoekt een vorm op alternatieve tekst in een PPTX-presentatie. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Zoekt een vorm op alternatieve tekst op een dia in een PPTX-presentatie. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Zoekt alle vormen op de opgegeven dia die overeenkomen met het opgegeven placeholdertype. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Wijzigt de plaatsing van alle vormen op de dia. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Wijzigt de plaatsing van geselecteerde vormen op de dia. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Wijzigt de plaatsing van alle vormen binnen een groepsvorm. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Wijzigt de plaatsing van geselecteerde vormen binnen een groepsvorm. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Zoekt en vervangt tekst in een presentatie met het opgegeven formaat. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Zoekt en vervangt tekst in een presentatie met het opgegeven formaat. |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Retourneert alle tekstframes op een dia in een PPTX-presentatie. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Retourneert alle tekstframes op de opgegeven dia die de opgegeven tekst bevatten. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Retourneert alle tekstframes in een PPTX-presentatie. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Converteert een bronbestandformaat naar de overeenkomende [SaveFormat](../../com.aspose.slides/saveformat). |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Zoekt een vorm op alternatieve tekst in een PPTX-presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Gescannde presentatie. |
| altText | java.lang.String | Alternatieve tekst van een vorm. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Shape of null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Zoekt een vorm op alternatieve tekst op een dia in een PPTX-presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Gescannde dia. |
| altText | java.lang.String | Alternatieve tekst van een vorm. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Shape of null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Zoekt alle vormen op de opgegeven dia die overeenkomen met het opgegeven placeholdertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | De dia waarop gezocht wordt naar vormen. |
| placeholderType | byte | Het type placeholder waarmee vormen worden gefilterd. |

**Returns:**
com.aspose.slides.IShape[] - Een array van [IShape](../../com.aspose.slides/ishape)-objecten die overeenkomen met het opgegeven placeholdertype.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Wijzigt de plaatsing van alle vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia of uit op elkaar.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | int | Bepaalt welk type uitlijning wordt toegepast. |
| alignToSlide | boolean | Indien true, worden vormen uitgelijnd ten opzichte van de dia-randen. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Bovenliggende dia. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Wijzigt de plaatsing van geselecteerde vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia of uit op elkaar.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | int | Bepaalt welk type uitlijning wordt toegepast. |
| alignToSlide | boolean | Indien true, worden vormen uitgelijnd ten opzichte van de dia-randen. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Bovenliggende dia. |
| shapeIndexes | int[] | Indexen van vormen die moeten worden uitgelijnd. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Wijzigt de plaatsing van alle vormen binnen een groepsvorm. Lijnt vormen uit op de marges of de rand van de dia of uit op elkaar.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | int | Bepaalt welk type uitlijning wordt toegepast. |
| alignToSlide | boolean | Indien true, worden vormen uitgelijnd ten opzichte van de dia-randen. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Bovenliggende groepsvorm. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Wijzigt de plaatsing van geselecteerde vormen binnen een groepsvorm. Lijnt vormen uit op de marges of de rand van de dia of uit op elkaar.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | int | Bepaalt welk type uitlijning wordt toegepast. |
| alignToSlide | boolean | Indien true, worden vormen uitgelijnd ten opzichte van de dia-randen. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Bovenliggende groepsvorm. |
| shapeIndexes | int[] | Indexen van vormen die moeten worden uitgelijnd. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Zoekt en vervangt tekst in een presentatie met het opgegeven formaat.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Gescannde presentatie. |
| withMasters | boolean | Bepaalt of master-dia’s moeten worden doorzocht. |
| find | java.lang.String | Te zoeken tekenreeks. |
| replace | java.lang.String | Tekenreeks waarmee de gevonden tekenreeks wordt vervangen. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Zoekt en vervangt tekst in een presentatie met het opgegeven formaat.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Gescannde presentatie. |
| withMasters | boolean | Bepaalt of master-dia’s moeten worden doorzocht. |
| find | java.lang.String | Te zoeken tekenreeks. |
| replace | java.lang.String | Tekenreeks waarmee de gevonden tekenreeks wordt vervangen. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Formaat voor het vervangen van tekstgedeelte. Indien null wordt het formaat van het eerste teken van de gevonden tekenreeks gebruikt. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Retourneert alle tekstframes op een dia in een PPTX-presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Gescannde dia. |

**Returns:**
com.aspose.slides.ITextFrame[] - Array van [TextFrame](../../com.aspose.slides/textframe)-objecten.
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Retourneert alle tekstframes op de opgegeven dia die de opgegeven tekst bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | De dia waarop gezocht wordt. |
| text | java.lang.String | De tekst die gezocht wordt in tekstframes. |
| checkPlaceholderText | boolean | Geeft aan of tekstframes die leeg zijn, maar waarvan de placeholder-tekst de zoektekst bevat, moeten worden meegenomen. |

**Returns:**
com.aspose.slides.ITextFrame[] - Een array van [ITextFrame](../../com.aspose.slides/itextframe)-objecten die de opgegeven tekst bevatten.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Retourneert alle tekstframes in een PPTX-presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Gescannde presentatie. |
| withMasters | boolean | Bepaalt of master-dia’s moeten worden doorzocht. |

**Returns:**
com.aspose.slides.ITextFrame[] - Array van [TextFrame](../../com.aspose.slides/textframe)-objecten.
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Converteert een bronbestandformaat naar de overeenkomende [SaveFormat](../../com.aspose.slides/saveformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | int | Het bronbestandformaat. |

**Returns:**
int - De overeenkomstige [SaveFormat](../../com.aspose.slides/saveformat)-waarde.