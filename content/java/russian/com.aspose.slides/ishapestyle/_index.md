---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Представляет ссылку на стиль фигуры.
type: docs
url: /ru/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Ссылка на стиль фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [getLineColor()](#getLineColor--) | Возвращает цвет контура фигуры. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Возвращает или задает индекс столбца линии в матрице стилей. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Возвращает или задает индекс столбца линии в матрице стилей. |
| [getFillColor()](#getFillColor--) | Возвращает цвет заливки фигуры. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Возвращает или задает индекс столбца заливки фигуры в матрицах стилей. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Возвращает или задает индекс столбца заливки фигуры в матрицах стилей. |
| [getEffectColor()](#getEffectColor--) | Возвращает цвет эффекта фигуры. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Возвращает или задает индекс столбца эффекта фигуры в матрице стилей. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Возвращает или задает индекс столбца эффекта фигуры в матрице стилей. |
| [getFontColor()](#getFontColor--) | Возвращает цвет шрифта фигуры. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Возвращает или задает индекс шрифта фигуры в коллекции шрифтов. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Возвращает или задает индекс шрифта фигуры в коллекции шрифтов. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Возвращает цвет контура фигуры. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Возвращает или задает индекс столбца линии в матрице стилей. Чтение/запись int.

**Возвращает:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Возвращает или задает индекс столбца линии в матрице стилей. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Возвращает цвет заливки фигуры. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Возвращает или задает индекс столбца заливки фигуры в матрицах стилей. 0 означает отсутствие заливки, положительное значение — индекс в стилях заливки темы, отрицательное значение — индекс в стилях фона темы. Чтение/запись short.

**Возвращает:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Возвращает или задает индекс столбца заливки фигуры в матрицах стилей. 0 означает отсутствие заливки, положительное значение — индекс в стилях заливки темы, отрицательное значение — индекс в стилях фона темы. Чтение/запись short.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Возвращает цвет эффекта фигуры. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Возвращает или задает индекс столбца эффекта фигуры в матрице стилей. Чтение/запись long.

**Возвращает:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Возвращает или задает индекс столбца эффекта фигуры в матрице стилей. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Возвращает цвет шрифта фигуры. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Возвращает или задает индекс шрифта фигуры в коллекции шрифтов. Чтение/запись [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Возвращает:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Возвращает или задает индекс шрифта фигуры в коллекции шрифтов. Чтение/запись [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |