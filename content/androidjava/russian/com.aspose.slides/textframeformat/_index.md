---
title: TextFrameFormat
second_title: Справочник API Aspose.Slides для Android через Java
description: Содержит свойства formatTextFrameFormatting TextFrames.
type: docs
url: /ru/com.aspose.slides/textframeformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Содержит свойства formatTextFrameFormatting TextFrame.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Инициализирует новый экземпляр класса [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Возвращает стиль текста. |
| [getThreeDFormat()](#getThreeDFormat--) | Возвращает объект ThreeDFormat, представляющий свойства 3d-эффекта для текста. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает или задает левый отступ (в пунктах) в TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Возвращает или задает левый отступ (в пунктах) в TextFrame. |
| [getMarginRight()](#getMarginRight--) | Возвращает или задает правый отступ (в пунктах) в TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Возвращает или задает правый отступ (в пунктах) в TextFrame. |
| [getMarginTop()](#getMarginTop--) | Возвращает или задает верхний отступ (в пунктах) в TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Возвращает или задает верхний отступ (в пунктах) в TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Возвращает или задает нижний отступ (в пунктах) в TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Возвращает или задает нижний отступ (в пунктах) в TextFrame. |
| [getWrapText()](#getWrapText--) | True, если текст переносится по границам TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True, если текст переносится по границам TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Возвращает или задает вертикальное привязывание текста в TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Возвращает или задает вертикальное привязывание текста в TextFrame. |
| [getCenterText()](#getCenterText--) | Если NullableBool.True, то текст должен быть центрирован в коробке по горизонтали. |
| [setCenterText(byte value)](#setCenterText-byte-) | Если NullableBool.True, то текст должен быть центрирован в коробке по горизонтали. |
| [getTextVerticalType()](#getTextVerticalType--) | Определяет ориентацию текста. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Определяет ориентацию текста. |
| [getAutofitType()](#getAutofitType--) | Возвращает или задает режим автоподгонки текста. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Возвращает или задает режим автоподгонки текста. |
| [getColumnCount()](#getColumnCount--) | Возвращает или задает количество столбцов в текстовой области. |
| [setColumnCount(int value)](#setColumnCount-int-) | Возвращает или задает количество столбцов в текстовой области. |
| [getColumnSpacing()](#getColumnSpacing--) | Возвращает или задает расстояние между столбцами текста в текстовой области (в пунктах). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Возвращает или задает расстояние между столбцами текста в текстовой области (в пунктах). |
| [getRotationAngle()](#getRotationAngle--) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. |
| [getTransform()](#getTransform--) | Получает или задает форму обтекания текста. |
| [setTransform(byte value)](#setTransform-byte-) | Получает или задает форму обтекания текста. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Получает или задает сохранение текста плоским, даже если применён эффект 3-D вращения. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Получает или задает сохранение текста плоским, даже если применён эффект 3-D вращения. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования текстового кадра с учётом наследования. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


Инициализирует новый экземпляр класса [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```


Версия. Только для чтения long.

**Возвращает:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


Возвращает стиль текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращает:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


Возвращает объект ThreeDFormat, представляющий свойства 3d-эффекта для текста. Только для чтения [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Установить преобразование текста
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Установить экструзию
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Установить контур
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Установить глубину
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Установить материал
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Установить освещение
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Установить тип камеры
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


Возвращает или задает левый отступ (в пунктах) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


Возвращает или задает левый отступ (в пунктах) в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


Возвращает или задает правый отступ (в пунктах) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


Возвращает или задает правый отступ (в пунктах) в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


Возвращает или задает верхний отступ (в пунктах) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


Возвращает или задает верхний отступ (в пунктах) в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Возвращает или задает нижний отступ (в пунктах) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


Возвращает или задает нижний отступ (в пунктах) в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


True, если текст переносится по границам TextFrame. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```


True, если текст переносится по границам TextFrame. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```


Возвращает или задает вертикальное привязывание текста в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращает:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


Возвращает или задает вертикальное привязывание текста в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


Если NullableBool.True, то текст должен быть центрирован в коробке по горизонтали. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


Если NullableBool.True, то текст должен быть центрирован в коробке по горизонтали. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Определяет ориентацию текста. Получаемое значение визуального поворота текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращает:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Определяет ориентацию текста. Получаемое значение визуального поворота текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


Возвращает или задает режим автоподгонки текста. Чтение/запись [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```


Возвращает или задает режим автоподгонки текста. Чтение/запись [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


Возвращает или задает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае будет установлено в ноль. Значение 0 означает неопределённое значение. Чтение/запись int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```


Возвращает или задает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае будет установлено в ноль. Значение 0 означает неопределённое значение. Чтение/запись int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```


Возвращает или задает расстояние между столбцами текста в текстовой области (в пунктах). Применяется только при наличии более одного столбца. Это значение должно быть положительным числом. В противном случае будет установлено в ноль. Чтение/запись double.

**Возвращает:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


Возвращает или задает расстояние между столбцами текста в текстовой области (в пунктах). Применяется только при наличии более одного столбца. Это значение должно быть положительным числом. В противном случае будет установлено в ноль. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется вращение сопутствующей формы. Если указано, применяется независимо от формы. Т.е. форма может иметь собственный угол вращения в дополнение к углу текста. Получаемое значение визуального поворота текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Рассмотрим случай, когда к фигуре применяется вращение на 90 градусов по часовой стрелке. 
>  В дополнение к этому, само текстовое тело имеет вращение на -90 градусов 
>  против часовой стрелки, применяемое к нему. Тогда результирующая фигура будет выглядеть
>  вращённой, но текст внутри неё будет выглядеть так, как будто он вообще не был вращён.
```

**Возвращает:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется вращение сопутствующей формы. Если указано, применяется независимо от формы. Т.е. форма может иметь собственный угол вращения в дополнение к углу текста. Получаемое значение визуального поворота текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Рассмотрим случай, когда к фигуре применяется вращение на 90 градусов по часовой стрелке. 
>  В дополнение к этому, само текстовое тело имеет вращение на -90 градусов 
>  против часовой стрелки, применяемое к нему. Затем получившаяся фигура будет выглядеть
>  повёрнутой, но текст внутри неё будет выглядеть так, как будто он вообще не был повёрнут.
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```


Получает или задает форму обтекания текста. Чтение/запись [TextShapeType](../../com.aspose.slides/textshapetype).

**Возвращает:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


Получает или задает форму обтекания текста. Чтение/запись [TextShapeType](../../com.aspose.slides/textshapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


Получает или задает сохранение текста плоским, даже если применён эффект 3-D вращения. Чтение/запись boolean.

**Возвращает:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


Получает или задает сохранение текста плоским, даже если применён эффект 3-D вращения. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


Получает эффективные данные форматирования текстового кадра с учётом наследования.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).