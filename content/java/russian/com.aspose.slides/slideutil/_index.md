---
title: SlideUtil
second_title: Справочник API Aspose.Slides для Java
description: Предлагает методы, помогающие искать фигуры и текст в презентации.
type: docs
url: /ru/com.aspose.slides/slideutil/
---
**Наследование:**
java.lang.Object
```
public class SlideUtil
```

Предлагает методы, помогающие искать фигуры и текст в презентации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Находит фигуру по альтернативному тексту в презентации PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Находит фигуру по альтернативному тексту на слайде в презентации PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Ищет все фигуры на указанном слайде, соответствующие заданному типу заполнителя. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Изменяет размещение всех фигур на слайде. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Изменяет размещение выбранных фигур на слайде. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Изменяет размещение всех фигур внутри групповой фигуры. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Изменяет размещение выбранных фигур внутри групповой фигуры. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Ищет и заменяет текст в презентации с заданным форматом. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Ищет и заменяет текст в презентации с заданным форматом. |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Возвращает все текстовые кадры на слайде в презентации PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Возвращает все текстовые кадры на указанном слайде, содержащие заданный текст. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Возвращает все текстовые кадры в презентации PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Преобразует исходный формат файла в соответствующий [SaveFormat](../../com.aspose.slides/saveformat). |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Find shape by alternative text in a PPTX presentation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Отсканированная презентация. |
| altText | java.lang.String | Альтернативный текст фигуры. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Shape или null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Find shape by alternative text on a slide in a PPTX presentation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Отсканированный слайд. |
| altText | java.lang.String | Альтернативный текст фигуры. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Shape или null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Searches for all shapes on the specified slide that match the given placeholder type.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Слайд для поиска фигур. |
| placeholderType | byte | Тип заполнителя для фильтрации фигур. |

**Возвращаемое значение:**
com.aspose.slides.IShape[] - Массив объектов [IShape](../../com.aspose.slides/ishape), соответствующих указанному типу заполнителя.
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


**Параметры:**
| Параметр | Тип | Описание |
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

**Параметры:**
| Параметр | Тип | Описание |
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

**Параметры:**
| Параметр | Тип | Описание |
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

**Параметры:**
| Параметр | Тип | Описание |
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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Отсканированная презентация. |
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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Отсканированная презентация. |
| withMasters | boolean | Determines whether master slides should be scanned. |
| find | java.lang.String | String value to find. |
| replace | java.lang.String | String value to replace. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format for replacing text portion. If null then will be used format of the first character of the found string |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Returns all text frames on a slide in a PPTX presentation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Отсканированный слайд. |

**Возвращаемое значение:**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Returns all text frames on the specified slide that contain the given text.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The slide to search. |
| text | java.lang.String | The text to search for within text frames. |
| checkPlaceholderText | boolean | Indicates whether to include text frames that are empty, but whose placeholder text contains the search text. |

**Возвращаемое значение:**
com.aspose.slides.ITextFrame[] - An array of [ITextFrame](../../com.aspose.slides/itextframe) objects that contain the specified text.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Returns all text frames in a PPTX presentation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Отсканированная презентация. |
| withMasters | boolean | Determines whether master slides should be scanned. |

**Возвращаемое значение:**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Converts a source file format to the corresponding [SaveFormat](../../com.aspose.slides/saveformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | int | The source file format. |

**Возвращаемое значение:**
int - The corresponding [SaveFormat](../../com.aspose.slides/saveformat) value.