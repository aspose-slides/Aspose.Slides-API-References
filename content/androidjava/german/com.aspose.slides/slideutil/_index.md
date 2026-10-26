---
title: SlideUtil
second_title: Aspose.Slides für Android über Java API Reference
description: Bietet Methoden, die bei der Suche nach Formen und Text in einer Präsentation helfen.
type: docs
url: /de/com.aspose.slides/slideutil/
---
**Inheritance:**
java.lang.Object
```
public class SlideUtil
```

Bietet Methoden, die bei der Suche nach Formen und Text in einer Präsentation helfen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Findet Form anhand des Alternativtexts in einer PPTX-Präsentation. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Findet Form anhand des Alternativtexts auf einer Folie in einer PPTX-Präsentation. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Sucht alle Formen auf der angegebenen Folie, die dem angegebenen Platzhaltertyp entsprechen. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Ändert die Anordnung aller Formen auf der Folie. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Ändert die Anordnung ausgewählter Formen auf der Folie. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Ändert die Anordnung aller Formen innerhalb einer Gruppierung. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Ändert die Anordnung ausgewählter Formen innerhalb einer Gruppierung. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Findet und ersetzt Text in einer Präsentation mit dem angegebenen Format |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Findet und ersetzt Text in einer Präsentation mit dem angegebenen Format |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Gibt alle Textbereiche auf einer Folie in einer PPTX-Präsentation zurück. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Gibt alle Textbereiche auf der angegebenen Folie zurück, die den angegebenen Text enthalten. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Gibt alle Textbereiche in einer PPTX-Präsentation zurück. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Konvertiert ein Quelldateiformat in das entsprechende [SaveFormat](../../com.aspose.slides/saveformat). |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Findet Form anhand des Alternativtexts in einer PPTX-Präsentation.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Durchsuchte Präsentation. |
| altText | java.lang.String | Alternativtext einer Form. |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - Shape oder null.

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Findet Form anhand des Alternativtexts auf einer Folie in einer PPTX-Präsentation.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Durchsuchte Folie. |
| altText | java.lang.String | Alternativtext einer Form. |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - Shape oder null.

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Sucht alle Formen auf der angegebenen Folie, die dem angegebenen Platzhaltertyp entsprechen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Die Folie, in der nach Formen gesucht wird. |
| placeholderType | byte | Der Typ des Platzhalters, nach dem Formen gefiltert werden sollen. |

**Rückgabe:**
com.aspose.slides.IShape[] - Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten, die dem angegebenen Platzhaltertyp entsprechen.

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Ändert die Anordnung aller Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | int | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | boolean | Wenn true, werden Formen relativ zu den Folienrändern ausgerichtet. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Eltern-Folie. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Ändert die Anordnung ausgewählter Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | int | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | boolean | Wenn true, werden Formen relativ zu den Folienrändern ausgerichtet. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Eltern-Folie. |
| shapeIndexes | int[] | Indizes der auszurichtenden Formen. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Ändert die Anordnung aller Formen innerhalb einer Gruppierung. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | int | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | boolean | Wenn true, werden Formen relativ zu den Folienrändern ausgerichtet. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Eltern-Gruppierungsform. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Ändert die Anordnung ausgewählter Formen innerhalb einer Gruppierung. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | int | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | boolean | Wenn true, werden Formen relativ zu den Folienrändern ausgerichtet. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Eltern-Gruppierungsform. |
| shapeIndexes | int[] | Indizes der auszurichtenden Formen. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Findet und ersetzt Text in einer Präsentation mit dem angegebenen Format

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Durchsuchte Präsentation. |
| withMasters | boolean | Bestimmt, ob Master-Folien durchsucht werden sollen. |
| find | java.lang.String | Zu suchender Zeichenkettenwert. |
| replace | java.lang.String | Zu ersetzender Zeichenkettenwert. Zeichen des gefundenen Strings |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

Findet und ersetzt Text in einer Präsentation mit dem angegebenen Format

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
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Durchsuchte Präsentation. |
| withMasters | boolean | Bestimmt, ob Master-Folien durchsucht werden sollen. |
| find | java.lang.String | Zu suchender Zeichenkettenwert. |
| replace | java.lang.String | Zu ersetzender Zeichenkettenwert. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format für den zu ersetzenden Textabschnitt. Wenn null, wird das Format des ersten Zeichens des gefundenen Strings verwendet |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Gibt alle Textbereiche auf einer Folie in einer PPTX-Präsentation zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Durchsuchte Folie. |

**Rückgabe:**
com.aspose.slides.ITextFrame[] - Array von [TextFrame](../../com.aspose.slides/textframe)-Objekten.

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Gibt alle Textbereiche auf der angegebenen Folie zurück, die den angegebenen Text enthalten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Die zu durchsuchende Folie. |
| text | java.lang.String | Der zu suchende Text in den Textbereichen. |
| checkPlaceholderText | boolean | Gibt an, ob leere Textbereiche berücksichtigt werden sollen, deren Platzhaltertext den gesuchten Text enthält. |

**Rückgabe:**
com.aspose.slides.ITextFrame[] - Ein Array von [ITextFrame](../../com.aspose.slides/itextframe)-Objekten, die den angegebenen Text enthalten.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Gibt alle Textbereiche in einer PPTX-Präsentation zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Durchsuchte Präsentation. |
| withMasters | boolean | Bestimmt, ob Master-Folien durchsucht werden sollen. |

**Rückgabe:**
com.aspose.slides.ITextFrame[] - Array von [TextFrame](../../com.aspose.slides/textframe)-Objekten.

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

Konvertiert ein Quelldateiformat in das entsprechende [SaveFormat](../../com.aspose.slides/saveformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | int | Das Quelldateiformat. |

**Rückgabe:**
int - Der entsprechende [SaveFormat](../../com.aspose.slides/saveformat)-Wert.