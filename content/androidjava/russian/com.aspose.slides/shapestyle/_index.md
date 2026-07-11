---
title: ShapeStyle
second_title: Aspose.Slides для Android через Java API справочник
description: Представляет ссылку на стиль фигур.
type: docs
url: /ru/com.aspose.slides/shapestyle/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

Представляет ссылку на стиль shape.
## Методы

| Method | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | Возвращает цвет контура shape. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Возвращает или задает индекс столбца line в матрице стиля. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Возвращает или задает индекс столбца line в матрице стиля. |
| [getFillColor()](#getFillColor--) | Возвращает цвет заливки shape. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Возвращает или задает индекс столбца заливки shape в матрицах стиля. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Возвращает или задает индекс столбца заливки shape в матрицах стиля. |
| [getEffectColor()](#getEffectColor--) | Возвращает цвет эффекта shape. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Возвращает или задает индекс столбца эффекта shape в матрице стиля. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Возвращает или задает индекс столбца эффекта shape в матрице стиля. |
| [getFontColor()](#getFontColor--) | Возвращает цвет шрифта shape. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Возвращает или задает индекс шрифта shape в коллекции шрифтов. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Возвращает или задает индекс шрифта shape в коллекции шрифтов. |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```


Возвращает цвет контура shape. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```


Возвращает или задает индекс столбца line в матрице стиля. Чтение/запись int.

**Возвращает:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```


Возвращает или задает индекс столбца line в матрице стиля. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```


Возвращает цвет заливки shape. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```


Возвращает или задает индекс столбца заливки shape в матрицах стиля. 0 означает отсутствие заливки, положительное значение — индекс в стилях заливки темы, отрицательное значение — индекс в стилях фона темы. Чтение/запись short.

**Возвращает:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```


Возвращает или задает индекс столбца заливки shape в матрицах стиля. 0 означает отсутствие заливки, положительное значение — индекс в стилях заливки темы, отрицательное значение — индекс в стилях фона темы. Чтение/запись short.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```


Возвращает цвет эффекта shape. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```


Возвращает или задает индекс столбца эффекта shape в матрице стиля. Чтение/запись long.

**Возвращает:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```


Возвращает или задает индекс столбца эффекта shape в матрице стиля. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```


Возвращает цвет шрифта shape. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```


Возвращает или задает индекс шрифта shape в коллекции шрифтов. Чтение/запись [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Возвращает:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```


Возвращает или задает индекс шрифта shape в коллекции шрифтов. Чтение/запись [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |