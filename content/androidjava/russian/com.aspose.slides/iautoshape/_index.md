---
title: IAutoShape
second_title: Справочник API Aspose.Slides для Android на Java
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
| [getAutoShapeLock()](#getAutoShapeLock--) | Возвращает блокировки AutoShape. |
| [getTextFrame()](#getTextFrame--) | Возвращает объект TextFrame для AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Определяет, должна ли эта автофигура быть заполнена фоном слайда вместо указанного стилем или форматом заполнения. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Определяет, должна ли эта автофигура быть заполнена фоном слайда вместо указанного стилем или форматом заполнения. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Добавляет новый TextFrame к фигуре. |
| [isTextBox()](#isTextBox--) | Определяет, является ли фигура текстовым полем. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

Возвращает блокировки AutoShape. Только для чтения [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Возвращает:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Возвращает объект TextFrame для AutoShape. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

Определяет, должна ли эта автофигура быть заполнена фоном слайда вместо указанного стилем или форматом заполнения. Чтение/запись boolean.

**Возвращает:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

Определяет, должна ли эта автофигура быть заполнена фоном слайда вместо указанного стилем или форматом заполнения. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

Добавляет новый TextFrame к фигуре. Если у фигуры уже есть TextFrame, то просто изменяет его текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст по умолчанию для нового TextFrame. |

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe) - Новый объект [ITextFrame](../../com.aspose.slides/itextframe).
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

Определяет, является ли фигура текстовым полем.

--------------------

Если фигура не указана как текстовое поле, это не означает, что к ней нельзя привязать текст. Текстовое поле — это лишь специализированная фигура со специфическими свойствами.

**Возвращает:**
boolean