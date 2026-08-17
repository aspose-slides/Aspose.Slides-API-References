---
title: SlideUtil
second_title: Aspose.Slides για Java Αναφορά API
description: Παρέχει μεθόδους που βοηθούν στην αναζήτηση σχημάτων και κειμένου σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/slideutil/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class SlideUtil
```

Παρέχει μεθόδους που βοηθούν στην αναζήτηση σχημάτων και κειμένου σε μια παρουσίαση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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


Find shape by alternative text in a PPTX presentation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Σαρωνόμενη παρουσίαση. |
| altText | java.lang.String | Εναλλακτικό κείμενο ενός σχήματος. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Shape ή null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Find shape by alternative text on a slide in a PPTX presentation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Σαρωνόμενη διαφάνεια. |
| altText | java.lang.String | Εναλλακτικό κείμενο ενός σχήματος. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Shape ή null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Searches for all shapes on the specified slide that match the given placeholder type.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Η διαφάνεια στην οποία γίνεται η αναζήτηση σχημάτων. |
| placeholderType | byte | Ο τύπος του placeholder με βάση τον οποίο φιλτράρονται τα σχήματα. |

**Επιστρέφει:**
com.aspose.slides.IShape[] - Ένας πίνακας αντικειμένων [IShape](../../com.aspose.slides/ishape) που ταιριάζουν με τον καθορισμένο τύπο placeholder.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

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


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Parent slide. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

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


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Changes the placement of all shapes within group shape. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Parent group shape. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Changes the placement of selected shapes within group shape. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Parent group shape. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Finds and replaces text in presentation with given format

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


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Σαρωνόμενη παρουσίαση. |
| withMasters | boolean | Determines whether master slides should be scanned. |
| find | java.lang.String | String value to find. |
| replace | java.lang.String | String value to replace. character of the found string |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Finds and replaces text in presentation with given format

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Σαρωνόμενη παρουσίαση. |
| withMasters | boolean | Determines whether master slides should be scanned. |
| find | java.lang.String | String value to find. |
| replace | java.lang.String | String value to replace. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format for replacing text portion. If null then will be used format of the first character of the found string |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Returns all text frames on a slide in a PPTX presentation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Σαρωνόμενη διαφάνεια. |

**Επιστρέφει:**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Returns all text frames on the specified slide that contain the given text.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Η διαφάνεια στην οποία γίνεται η αναζήτηση. |
| text | java.lang.String | Το κείμενο που αναζητείται εντός των πλαισίων κειμένου. |
| checkPlaceholderText | boolean | Indicates whether to include text frames that are empty, but whose placeholder text contains the search text. |

**Επιστρέφει:**
com.aspose.slides.ITextFrame[] - An array of [ITextFrame](../../com.aspose.slides/itextframe) objects that contain the specified text.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Returns all text frames in a PPTX presentation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Σαρωνόμενη παρουσίαση. |
| withMasters | boolean | Determines whether master slides should be scanned. |

**Επιστρέφει:**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Converts a source file format to the corresponding [SaveFormat](../../com.aspose.slides/saveformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | int | The source file format. |

**Επιστρέφει:**
int - The corresponding [SaveFormat](../../com.aspose.slides/saveformat) value.