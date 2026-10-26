---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /ru/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Содержит свойства форматирования TextFrame.
## Методы

| Метод | Описание |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Возвращает стиль текста. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает или задает левый отступ (в пунктах) в TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Возвращает или задает левый отступ (в пунктах) в TextFrame. |
| [getMarginRight()](#getMarginRight--) | Возвращает или задает правый отступ (в пунктах) в TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Возвращает или задает правый отступ (в пунктах) в TextFrame. |
| [getMarginTop()](#getMarginTop--) | Возвращает или задает верхний отступ (в пунктах) в TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Возвращает или задает верхний отступ (в пунктах) в TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Возвращает или задает нижний отступ (в пунктах) в TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Возвращает или задает нижний отступ (в пунктах) в TextFrame. |
| [getWrapText()](#getWrapText--) | True, если текст переносится по полям TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True, если текст переносится по полям TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Возвращает или задает вертикальный якорный текст в TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Возвращает или задает вертикальный якорный текст в TextFrame. |
| [getCenterText()](#getCenterText--) | Если NullableBool.True, то текст должен быть центрован по горизонтали в блоке. |
| [setCenterText(byte value)](#setCenterText-byte-) | Если NullableBool.True, то текст должен быть центрован по горизонтали в блоке. |
| [getTextVerticalType()](#getTextVerticalType--) | Определяет ориентацию текста. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Определяет ориентацию текста. |
| [getAutofitType()](#getAutofitType--) | Возвращает или задает режим автоподгонки текста. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Возвращает или задает режим автоподгонки текста. |
| [getColumnCount()](#getColumnCount--) | Возвращает или задает количество колонок в текстовой области. |
| [setColumnCount(int value)](#setColumnCount-int-) | Возвращает или задает количество колонок в текстовой области. |
| [getColumnSpacing()](#getColumnSpacing--) | Возвращает или задает расстояние между колонками текста в текстовой области (в пунктах). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Возвращает или задает расстояние между колонками текста в текстовой области (в пунктах). |
| [getThreeDFormat()](#getThreeDFormat--) | Возвращает объект ThreeDFormat, представляющий свойства 3D-эффекта для текста. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Возвращает или задает полное исключение текста из 3D-сцены. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Возвращает или задает полное исключение текста из 3D-сцены. |
| [getRotationAngle()](#getRotationAngle--) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. |
| [getTransform()](#getTransform--) | Возвращает или задает форму переноса текста. |
| [setTransform(byte value)](#setTransform-byte-) | Возвращает или задает форму переноса текста. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования текстового кадра с учётом наследования. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```


Возвращает стиль текста. Точно только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращает:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Возвращает или задает левый отступ (в пунктах) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Возвращает или задает левый отступ (в пунктах) в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Возвращает или задает правый отступ (в пунктах) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Возвращает или задает правый отступ (в пунктах) в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Возвращает или задает верхний отступ (в пунктах) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Возвращает или задает верхний отступ (в пунктах) в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Возвращает или задает нижний отступ (в пунктах) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Возвращает или задает нижний отступ (в пунктах) в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


True, если текст переносится по полям TextFrame. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


True, если текст переносится по полям TextFrame. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Возвращает или задает вертикальный якорный текст в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращает:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Возвращает или задает вертикальный якорный текст в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


Если NullableBool.True, то текст должен быть центрован по горизонтали в блоке. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Если NullableBool.True, то текст должен быть центрован по горизонтали в блоке. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Определяет ориентацию текста. Итоговое значение визуального поворота текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращает:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Определяет ориентацию текста. Итоговое значение визуального поворота текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Возвращает или задает режим автоподгонки текста. Чтение/запись [TextAutofitType](../../com.aspose.slides/textautofittype).

**Возвращает:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Возвращает или задает режим автоподгонки текста. Чтение/запись [TextAutofitType](../../com.aspose.slides/textautofittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Возвращает или задает количество колонок в текстовой области. Это значение должно быть положительным. В противном случае оно будет установлено в ноль. Значение 0 означает неопределённое значение. Чтение/запись int.

**Возвращает:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```


Возвращает или задает количество колонок в текстовой области. Это значение должно быть положительным. В противном случае оно будет установлено в ноль. Значение 0 означает неопределённое значение. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```


Возвращает или задает расстояние между колонками текста в текстовой области (в пунктах). Применяется только при наличии более одной колонки. Это значение должно быть положительным. В противном случае оно будет установлено в ноль. Чтение/запись double.

**Возвращает:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```


Возвращает или задает расстояние между колонками текста в текстовой области (в пунктах). Применяется только при наличии более одной колонки. Это значение должно быть положительным. В противном случае оно будет установлено в ноль. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Возвращает объект ThreeDFormat, представляющий свойства 3D-эффекта для текста. Точно только для чтения [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Установить трансформацию текста
>      // Установить экструзию
>      // Установить контур
>      // Установить глубину
>      // Установить материал
>      // Установить освещение
>      // Установить тип камеры
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
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```


Возвращает или задает полное исключение текста из 3D-сцены. Чтение/запись boolean.

**Возвращает:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```


Возвращает или задает полное исключение текста из 3D-сцены. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется поворот сопутствующей фигуры. Если указано, то применяется независимо от фигуры. То есть у фигуры может быть свой поворот, а у текста — свой. Итоговое значение визуального поворота текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Рассмотрите случай, когда к фигуре применяется поворот на 90 градусов по часовой стрелке. 
>  В дополнение к этому само текстовое поле имеет поворот на -90 градусов 
>  против часовой стрелки, примененный к нему. Затем получившаяся фигура будет выглядеть как
>  повернутая, но текст внутри нее будет выглядеть так, как будто он вовсе не был повернут.
> ```


**Возвращает:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется поворот сопутствующей фигуры. Если указано, то применяется независимо от фигуры. То есть у фигуры может быть свой поворот, а у текста — свой. Итоговое значение визуального поворота текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Рассмотрите случай, когда к фигуре применяется поворот на 90 градусов по часовой стрелке. 
>  В дополнение к этому само текстовое тело имеет поворот на -90 градусов 
>  против часовой стрелки, применённый к нему. Затем получившаяся фигура будет выглядеть как
>  повёрнутая, но текст внутри неё будет выглядеть так, как будто он вовсе не был повернут.
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```


Возвращает или задает форму переноса текста. Чтение/запись [TextShapeType](../../com.aspose.slides/textshapetype).

**Возвращает:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```


Возвращает или задает форму переноса текста. Чтение/запись [TextShapeType](../../com.aspose.slides/textshapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```


Получает эффективные данные форматирования текстового кадра с учётом наследования.

**Возвращает:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).