---
title: AutoShape
second_title: Справочник API Aspose.Slides для Java
description: Представляет AutoShape.
type: docs
url: /ru/com.aspose.slides/autoshape/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Все реализованные интерфейсы:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Представляет AutoShape.
## Методы

| Метод | Описание |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Возвращает блокировки фигуры. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Возвращает блокировки автоконтуры. |
| [getTextFrame()](#getTextFrame--) | Возвращает объект TextFrame для AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Определяет, должна ли эта автоконтур быть заполнена фоновым заливкой слайда вместо указанной в стиле или формате заливки. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Определяет, должна ли эта автоконтур быть заполнена фоновым заливкой слайда вместо указанной в стиле или формате заливки. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Добавляет новый TextFrame к фигуре. |
| [isTextBox()](#isTextBox--) | Указывает, является ли фигура текстовым полем. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Возвращает блокировки фигуры. Только для чтения [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Возвращаемое значение:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Возвращает блокировки автоконтуры. Только для чтения [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Возвращаемое значение:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Возвращает объект TextFrame для AutoShape. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Определяет, должна ли эта автоконтур быть заполнена фоновым заливкой слайда вместо указанной в стиле или формате заливки. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Определяет, должна ли эта автоконтур быть заполнена фоновым заливкой слайда вместо указанной в стиле или формате заливки. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Добавляет новый TextFrame к фигуре. Если у фигуры уже есть TextFrame, то просто изменяет её текст.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // Создаёт объект Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Получает первый слайд в презентации
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Добавляет AutoShape с типом Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Добавляет TextFrame к Rectangle
>      ashp.addTextFrame(" ");
>      // Получает доступ к текстовому фрейму
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Создаёт объект Paragraph для текстового фрейма
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Создаёт объект Portion для абзаца
>      IPortion portion = para.getPortions().get_Item(0);
>      // Устанавливает текст
>      portion.setText("Aspose TextBox");
>      // Сохраняет презентацию на диск
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Получает первый слайд в презентации
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Добавляет AutoShape с типом Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Добавляет TextFrame к Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Получает формат текста TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Указывает количество колонок в TextFrame
>      format.setColumnCount(3);
>      // Указывает расстояние между колонками
>      format.setColumnSpacing(10);
>      // Сохраняет презентацию
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст по умолчанию для нового TextFrame. |

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Указывает, является ли фигура текстовым полем.

--------------------

Если фигура не указана как текстовое поле, это не означает, что к ней нельзя прикрепить текст. Текстовое поле — это лишь специализированная фигура со специфическими свойствами.

**Возвращаемое значение:**
boolean