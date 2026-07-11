---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Represent shapes style reference.
type: docs
url: /ru/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Представляет ссылку на стиль формы.

## Методы

| Метод | Описание |
| --- | --- |
| [getLineColor()](#getLineColor--) | Возвращает цвет контура формы. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Возвращает или задаёт индекс столбца линии в матрице стилей. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Возвращает или задаёт индекс столбца линии в матрице стилей. |
| [getFillColor()](#getFillColor--) | Возвращает цвет заливки формы. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Возвращает или задаёт индекс столбца заливки формы в матрицах стилей. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Возвращает или задаёт индекс столбца заливки формы в матрицах стилей. |
| [getEffectColor()](#getEffectColor--) | Возвращает цвет эффекта формы. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Возвращает или задаёт индекс столбца эффекта формы в матрице стилей. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Возвращает или задаёт индекс столбца эффекта формы в матрице стилей. |
| [getFontColor()](#getFontColor--) | Возвращает цвет шрифта формы. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Возвращает или задаёт индекс шрифта формы в коллекции шрифтов. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Возвращает или задаёт индекс шрифта формы в коллекции шрифтов. |

### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Возвращает цвет контура формы. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Возвращает или задаёт индекс столбца линии в матрице стилей. Чтение/запись int.

**Возвращает:**
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Возвращает или задаёт индекс столбца линии в матрице стилей. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Возвращает цвет заливки формы. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Возвращает или задаёт индекс столбца заливки формы в матрицах стилей. 0 означает отсутствие заливки, положительное значение — индекс в стилах заливки темы, отрицательное значение — индекс в стилах фона темы. Чтение/запись short.

**Возвращает:**
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Возвращает или задаёт индекс столбца заливки формы в матрицах стилей. 0 означает отсутствие заливки, положительное значение — индекс в стилах заливки темы, отрицательное значение — индекс в стилах фона темы. Чтение/запись short.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Возвращает цвет эффекта формы. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Возвращает или задаёт индекс столбца эффекта формы в матрице стилей. Чтение/запись long.

**Возвращает:**
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Возвращает или задаёт индекс столбца эффекта формы в матрице стилей. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Возвращает цвет шрифта формы. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Возвращает или задаёт индекс шрифта формы в коллекции шрифтов. Чтение/запись [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Возвращает:**
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Возвращает или задаёт индекс шрифта формы в коллекции шрифтов. Чтение/запись [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |