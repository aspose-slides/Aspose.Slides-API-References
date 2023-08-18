---
title: SlideUtil
second_title: Aspose.Slides for Android via Java API Reference
description: Offer methods which help to search shapes and text in a presentation.
type: docs
weight: 515
url: /com.aspose.slides/slideutil/
---
**Inheritance:**
java.lang.Object
```
public class SlideUtil
```

Offer methods which help to search shapes and text in a presentation.
## Constructors

| Constructor | Description |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Methods

| Method | Description |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Find shape by alternative text in a PPTX presentation. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Find shape by alternative text on a slide in a PPTX presentation. |
| [alignShapes(int alignmentType, boolean alignToSlide, IShapeCollection shapes)](#alignShapes-int-boolean-com.aspose.slides.IShapeCollection-) | Changes the placement of all shapes in the collection. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Changes the placement of all shapes on the slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Changes the placement of selected shapes on the slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Changes the placement of all shapes within group shape. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Changes the placement of selected shapes within group shape. |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Returns all text frames on a slide in a PPTX presentation. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Returns all text frames in a PPTX presentation. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Find shape by alternative text in a PPTX presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| altText | java.lang.String | Alternative text of a shape. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Shape or null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Find shape by alternative text on a slide in a PPTX presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Scanned slide. |
| altText | java.lang.String | Alternative text of a shape. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Shape or null.
### alignShapes(int alignmentType, boolean alignToSlide, IShapeCollection shapes) {#alignShapes-int-boolean-com.aspose.slides.IShapeCollection-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IShapeCollection shapes)
```


Changes the placement of all shapes in the collection. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0).getShapes());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Shapes collection to be aligned |

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

**Parameters:**
| Parameter | Type | Description |
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

**Parameters:**
| Parameter | Type | Description |
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

**Parameters:**
| Parameter | Type | Description |
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Parent group shape. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Returns all text frames on a slide in a PPTX presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Scanned slide. |

**Returns:**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Returns all text frames in a PPTX presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| withMasters | boolean | Determines whether master slides should be scanned. |

**Returns:**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.
