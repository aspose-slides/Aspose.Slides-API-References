---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
description: Represents format of a table cell.
type: docs
url: /ru/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Представляет формат ячейки таблицы.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Возвращает объект свойств заливки ячейки. |
| [getBorderLeft()](#getBorderLeft--) | Возвращает объект свойств левой границы линии. |
| [getBorderTop()](#getBorderTop--) | Возвращает объект свойств верхней границы линии. |
| [getBorderRight()](#getBorderRight--) | Возвращает объект свойств правой границы линии. |
| [getBorderBottom()](#getBorderBottom--) | Возвращает объект свойств нижней границы линии. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Возвращает объект свойств диагональной линии сверху-слева вниз-вправо. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Возвращает объект свойств диагональной линии снизу-слева вверх-вправо. |
| [getTransparency()](#getTransparency--) | Получает или задает прозрачность цвета заливки. |
| [setTransparency(float value)](#setTransparency-float-) | Получает или задает прозрачность цвета заливки. |
| [getEffective()](#getEffective--) | Получает эффективные свойства форматирования ячейки таблицы с учётом наследования и применённых стилей таблицы. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Возвращает объект свойств заливки ячейки. Только чтение [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Возвращает объект свойств левой границы линии. Только чтение [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Возвращает объект свойств верхней границы линии. Только чтение [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Возвращает объект свойств правой границы линии. Только чтение [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Возвращает объект свойств нижней границы линии. Только чтение [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Возвращает объект свойств диагональной линии сверху-слева вниз-вправо. Только чтение [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Возвращает объект свойств диагональной линии снизу-слева вверх-вправо. Только чтение [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Получает или задает прозрачность цвета заливки. Чтение/запись  float .

**Возвращает:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Получает или задает прозрачность цвета заливки. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Получает эффективные свойства форматирования ячейки таблицы с учётом наследования и применённых стилей таблицы.

**Возвращает:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).