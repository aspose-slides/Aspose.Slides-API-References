---
title: SlideUtil
second_title: Aspose.Slides для Android через справочник Java API
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
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Находит и заменяет текст в презентации с заданным форматом |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Находит и заменяет текст в презентации с заданным форматом |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Возвращает все текстовые фреймы на слайде в презентации PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Возвращает все текстовые фреймы на указанном слайде, содержащие заданный текст. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Возвращает все текстовые фреймы в презентации PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Конвертирует исходный формат файла в соответствующий [SaveFormat](../../com.aspose.slides/saveformat). |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Находит фигуру по альтернативному тексту в презентации PPTX.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Сканированная презентация. |
| altText | java.lang.String | Альтернативный текст фигуры. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Shape or null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Находит фигуру по альтернативному тексту на слайде в презентации PPTX.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Сканированный слайд. |
| altText | java.lang.String | Альтернативный текст фигуры. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Shape or null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Ищет все фигуры на указанном слайде, соответствующие заданному типу заполнителя.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Слайд для поиска фигур. |
| placeholderType | byte | Тип заполнителя для фильтрации фигур. |

**Возвращаемое значение:**
com.aspose.slides.IShape[] - массив объектов [IShape](../../com.aspose.slides/ishape), соответствующих указанному типу заполнителя.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Изменяет размещение всех фигур на слайде. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.

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
| alignmentType | int | Определяет, какой тип выравнивания будет применён. |
| alignToSlide | boolean | Если true, фигуры будут выравнены относительно краев слайда. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Родительский слайд. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Изменяет размещение выбранных фигур на слайде. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.

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
| alignmentType | int | Определяет, какой тип выравнивания будет применён. |
| alignToSlide | boolean | Если true, фигуры будут выравнены относительно краёв слайда. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Родительский слайд. |
| shapeIndexes | int[] | Индексы фигур, которые необходимо выровнять. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Изменяет размещение всех фигур внутри групповой фигуры. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.

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
| alignmentType | int | Определяет, какой тип выравнивания будет применён. |
| alignToSlide | boolean | Если true, фигуры будут выравнены относительно краёв слайда. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Родительская групповая фигура. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Изменяет размещение выбранных фигур внутри групповой фигуры. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.

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
| alignmentType | int | Определяет, какой тип выравнивания будет применён. |
| alignToSlide | boolean | Если true, фигуры будут выравнены относительно краёв слайда. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Родительская групповая фигура. |
| shapeIndexes | int[] | Индексы фигур, которые необходимо выровнять. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Находит и заменяет текст в презентации с заданным форматом

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
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Сканированная презентация. |
| withMasters | boolean | Определяет, следует ли сканировать слайды-мастера. |
| find | java.lang.String | Строка для поиска. |
| replace | java.lang.String | Строка, которой будет заменено найденное значение. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Находит и заменяет текст в презентации с заданным форматом

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Сканированная презентация. |
| withMasters | boolean | Определяет, следует ли сканировать слайды-мастера. |
| find | java.lang.String | Строка для поиска. |
| replace | java.lang.String | Строка, которой будет заменено найденное значение. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Формат заменяемой части текста. Если null, будет использован формат первого символа найденной строки. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Возвращает все текстовые фреймы на слайде в презентации PPTX.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Сканированный слайд. |

**Возвращаемое значение:**
com.aspose.slides.ITextFrame[] - массив объектов [TextFrame](../../com.aspose.slides/textframe).
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Возвращает все текстовые фреймы на указанном слайде, содержащие заданный текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Слайд для поиска. |
| text | java.lang.String | Текст для поиска внутри текстовых фреймов. |
| checkPlaceholderText | boolean | Указывает, следует ли включать пустые текстовые фреймы, у которых текст заполнителя содержит искомый текст. |

**Возвращаемое значение:**
com.aspose.slides.ITextFrame[] - массив объектов [ITextFrame](../../com.aspose.slides/itextframe), содержащих указанный текст.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Возвращает все текстовые фреймы в презентации PPTX.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Сканированная презентация. |
| withMasters | boolean | Определяет, следует ли сканировать слайды-мастера. |

**Возвращаемое значение:**
com.aspose.slides.ITextFrame[] - массив объектов [TextFrame](../../com.aspose.slides/textframe).
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Конвертирует исходный формат файла в соответствующий [SaveFormat](../../com.aspose.slides/saveformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | int | Исходный формат файла. |

**Возвращаемое значение:**
int - Соответствующее значение [SaveFormat](../../com.aspose.slides/saveformat).