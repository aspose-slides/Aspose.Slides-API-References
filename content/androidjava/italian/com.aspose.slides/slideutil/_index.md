---
title: SlideUtil
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Offre metodi che aiutano a cercare forme e testo in una presentazione.
type: docs
url: /it/com.aspose.slides/slideutil/
---
**Eredità:**
java.lang.Object
```
public class SlideUtil
```

Offre metodi che aiutano a cercare forme e testo in una presentazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Find shape by alternative text in a PPTX presentation. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Find shape by alternative text on a slide in a PPTX presentation. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Searches for all shapes on the specified slide that match the given placeholder type. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Changes the placement of all shapes on the slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Changes the placement of selected shapes on the slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Changes the placement of all shapes within group shape. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Changes the placement of selected shapes within group shape. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Finds and replaces text in presentation with given format |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Finds and replaces text in presentation with given format |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Returns all text frames on a slide in a PPTX presentation. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Returns all text frames on the specified slide that contain the given text. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Returns all text frames in a PPTX presentation. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Converts a source file format to the corresponding [SaveFormat](../../com.aspose.slides/saveformat). |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Trova la forma tramite testo alternativo in una presentazione PPTX.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione scansionata. |
| altText | java.lang.String | Testo alternativo di una forma. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Shape o null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Trova la forma tramite testo alternativo su una diapositiva in una presentazione PPTX.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva scansionata. |
| altText | java.lang.String | Testo alternativo di una forma. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Shape o null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Cerca tutte le forme nella diapositiva specificata che corrispondono al tipo di segnaposto fornito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La diapositiva su cui cercare le forme. |
| placeholderType | byte | Il tipo di segnaposto per filtrare le forme. |

**Restituisce:**
com.aspose.slides.IShape[] - Un array di [IShape](../../com.aspose.slides/ishape) objects che corrispondono al tipo di segnaposto specificato.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Modifica la disposizione di tutte le forme sulla diapositiva. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignmentType | int | Determina quale tipo di allineamento verrà applicato. |
| alignToSlide | boolean | Se true, le forme verranno allineate rispetto ai bordi della diapositiva. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva padre. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Modifica la disposizione delle forme selezionate sulla diapositiva. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignmentType | int | Determina quale tipo di allineamento verrà applicato. |
| alignToSlide | boolean | Se true, le forme verranno allineate rispetto ai bordi della diapositiva. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva padre. |
| shapeIndexes | int[] | Indici delle forme da allineare. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Modifica la disposizione di tutte le forme all'interno del gruppo di forme. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignmentType | int | Determina quale tipo di allineamento verrà applicato. |
| alignToSlide | boolean | Se true, le forme verranno allineate rispetto ai bordi della diapositiva. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Gruppo di forme padre. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Modifica la disposizione delle forme selezionate all'interno del gruppo di forme. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignmentType | int | Determina quale tipo di allineamento verrà applicato. |
| alignToSlide | boolean | Se true, le forme verranno allineate rispetto ai bordi della diapositiva. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Gruppo di forme padre. |
| shapeIndexes | int[] | Indici delle forme da allineare. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Trova e sostituisce il testo nella presentazione con il formato fornito

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione scansionata. |
| withMasters | boolean | Determina se le diapositive master devono essere scansionate. |
| find | java.lang.String | Valore stringa da trovare. |
| replace | java.lang.String | Valore stringa da sostituire. carattere della stringa trovata |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Trova e sostituisce il testo nella presentazione con il formato fornito

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione scansionata. |
| withMasters | boolean | Determina se le diapositive master devono essere scansionate. |
| find | java.lang.String | Valore stringa da trovare. |
| replace | java.lang.String | Valore stringa da sostituire. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Formato per sostituire la porzione di testo. Se null verrà usato il formato del primo carattere della stringa trovata |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Restituisce tutti i fotogrammi di testo su una diapositiva in una presentazione PPTX.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva scansionata. |

**Restituisce:**
com.aspose.slides.ITextFrame[] - Array di [TextFrame](../../com.aspose.slides/textframe) objects.

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Restituisce tutti i fotogrammi di testo sulla diapositiva specificata che contengono il testo fornito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La diapositiva da cercare. |
| text | java.lang.String | Il testo da cercare nei fotogrammi di testo. |
| checkPlaceholderText | boolean | Indica se includere i fotogrammi di testo vuoti, ma il cui testo segnaposto contiene il testo di ricerca. |

**Restituisce:**
com.aspose.slides.ITextFrame[] - Un array di [ITextFrame](../../com.aspose.slides/itextframe) objects che contengono il testo specificato.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Restituisce tutti i fotogrammi di testo in una presentazione PPTX.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione scansionata. |
| withMasters | boolean | Determina se le diapositive master devono essere scansionate. |

**Restituisce:**
com.aspose.slides.ITextFrame[] - Array di [TextFrame](../../com.aspose.slides/textframe) objects.

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Converte un formato di file sorgente nel corrispondente [SaveFormat](../../com.aspose.slides/saveformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | int | Il formato di file sorgente. |

**Restituisce:**
int - Il valore [SaveFormat](../../com.aspose.slides/saveformat) corrispondente.