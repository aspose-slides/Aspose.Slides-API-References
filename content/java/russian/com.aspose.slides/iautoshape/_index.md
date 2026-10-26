---
title: IAutoShape
second_title: Справочник API Aspose.Slides для Java
description: Представляет AutoShape.
type: docs
url: /ru/com.aspose.slides/iautoshape/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Представляет AutoShape.
## Методы

| Метод | Описание |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Возвращает AutoShape's locks. Только для чтения [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Возвращаемое значение:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Возвращает объект TextFrame для AutoShape. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Определяет, следует ли заполнять эту автофигуру фоном слайда вместо того, что указано в стиле или формате заполнения. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Определяет, следует ли заполнять эту автофигуру фоном слайда вместо того, что указано в стиле или формате заполнения. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Добавляет новый TextFrame к фигуре. Если у фигуры уже есть TextFrame, то просто меняет её текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст по умолчанию для нового TextFrame. |

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe) - New [ITextFrame](../../com.aspose.slides/itextframe) object.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Указывает, является ли фигура текстовым полем.

--------------------

Если фигура не указана как текстовое поле, это не значит, что к ней нельзя прикрепить текст. Текстовое поле — это просто специализированная фигура со специфическими свойствами.

**Возвращаемое значение:**
boolean