---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: Содержит свойства форматирования TextFrames.
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
| [getMarginLeft()](#getMarginLeft--) | Возвращает или задает левый отступ (points) в TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Возвращает или задает левый отступ (points) в TextFrame. |
| [getMarginRight()](#getMarginRight--) | Возвращает или задает правый отступ (points) в TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Возвращает или задает правый отступ (points) в TextFrame. |
| [getMarginTop()](#getMarginTop--) | Возвращает или задает верхний отступ (points) в TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Возвращает или задает верхний отступ (points) в TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Возвращает или задает нижний отступ (points) в TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Возвращает или задает нижний отступ (points) в TextFrame. |
| [getWrapText()](#getWrapText--) | True если текст переносится по полям TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True если текст переносится по полям TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Возвращает или задает вертикальное привязку текста в TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Возвращает или задает вертикальное привязку текста в TextFrame. |
| [getCenterText()](#getCenterText--) | Если NullableBool.True, то текст должен быть центрирован в коробке по горизонтали. |
| [setCenterText(byte value)](#setCenterText-byte-) | Если NullableBool.True, то текст должен быть центрирован в коробке по горизонтали. |
| [getTextVerticalType()](#getTextVerticalType--) | Определяет ориентацию текста. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Определяет ориентацию текста. |
| [getAutofitType()](#getAutofitType--) | Возвращает или задает режим автоподгонки текста. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Возвращает или задает режим автоподгонки текста. |
| [getColumnCount()](#getColumnCount--) | Возвращает или задает количество столбцов в области текста. |
| [setColumnCount(int value)](#setColumnCount-int-) | Возвращает или задает количество столбцов в области текста. |
| [getColumnSpacing()](#getColumnSpacing--) | Возвращает или задает расстояние между столбцами текста в области текста (в points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Возвращает или задает расстояние между столбцами текста в области текста (в points). |
| [getThreeDFormat()](#getThreeDFormat--) | Возвращает объект ThreeDFormat, представляющий свойства 3d-эффекта для текста. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Возвращает или задает полное исключение текста из 3D-сцены. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Возвращает или задает полное исключение текста из 3D-сцены. |
| [getRotationAngle()](#getRotationAngle--) | Указывает пользовательский поворот, применяемый к тексту внутри ограничивающего прямоугольника. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Указывает пользовательский поворот, применяемый к тексту внутри ограничивающего прямоугольника. |
| [getTransform()](#getTransform--) | Получает или задает форму обтекания текста. |
| [setTransform(byte value)](#setTransform-byte-) | Получает или задает форму обтекания текста. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования текстового фрейма с примененным наследованием. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Возвращает стиль текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращает:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Возвращает или задает левый отступ (points) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Возвращает или задает левый отступ (points) в TextFrame. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Возвращает или задает правый отступ (points) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Возвращает или задает правый отступ (points) в TextFrame. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Возвращает или задает верхний отступ (points) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Возвращает или задает верхний отступ (points) в TextFrame. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Возвращает или задает нижний отступ (points) в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Возвращает или задает нижний отступ (points) в TextFrame. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True если текст переносится по полям TextFrame. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True если текст переносится по полям TextFrame. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Возвращает или задает вертикальное привязку текста в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращает:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Возвращает или задает вертикальное привязку текста в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Если NullableBool.True, то текст должен быть центрирован в коробке по горизонтали. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Если NullableBool.True, то текст должен быть центрирован в коробке по горизонтали. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Определяет ориентацию текста. Получаемое значение визуального вращения текста, получаемое из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращает:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Определяет ориентацию текста. Получаемое значение визуального вращения текста, получаемое из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Параметры:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Возвращает или задает количество столбцов в области текста. Это значение должно быть положительным. В противном случае значение будет установлено в 0. Значение 0 означает неопределённое значение. Чтение/запись int.

**Возвращает:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Возвращает или задает количество столбцов в области текста. Это значение должно быть положительным. В противном случае значение будет установлено в 0. Значение 0 означает неопределённое значение. Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Возвращает или задает расстояние между столбцами текста в области текста (в points). Это применимо только когда присутствует более 1 столбца. Это значение должно быть положительным. В противном случае значение будет установлено в 0. Чтение/запись double.

**Возвращает:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Возвращает или задает расстояние между столбцами текста в области текста (в points). Это применимо только когда присутствует более 1 столбца. Это значение должно быть положительным. В противном случае значение будет установлено в 0. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Возвращает объект ThreeDFormat, представляющий свойства 3d-эффекта для текста. Только для чтения [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Установить трансформацию текста
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Указывает пользовательский поворот, применяемый к тексту внутри ограничивающего прямоугольника. Если не указан, используется поворот сопутствующей фигуры. Если указан, то применяется независимо от фигуры. То есть фигура может иметь поворот, дополнительно к повороту самого текста. Получаемое значение визуального вращения текста, получаемое из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Возвращает:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Указывает пользовательский поворот, применяемый к тексту внутри ограничивающего прямоугольника. Если не указан, используется поворот сопутствующей фигуры. Если указан, то применяется независимо от фигуры. То есть фигура может иметь поворот, дополнительно к повороту самого текста. Получаемое значение визуального вращения текста, получаемое из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Получает или задает форму обтекания текста. Чтение/запись [TextShapeType](../../com.aspose.slides/textshapetype).

**Возвращает:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Получает или задает форму обтекания текста. Чтение/запись [TextShapeType](../../com.aspose.slides/textshapetype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Получает эффективные данные форматирования текстового фрейма с примененным наследованием.

**Возвращает:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).