---
title: Cell
second_title: Справочник API Aspose.Slides для Java
description: Представляет ячейку таблицы.
type: docs
url: /ru/com.aspose.slides/cell/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Представляет ячейку таблицы.
## Методы

| Метод | Описание |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Возвращает расстояние от левой стороны таблицы до левой стороны ячейки. |
| [getOffsetY()](#getOffsetY--) | Возвращает расстояние от верхней стороны таблицы до верхней стороны ячейки. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Возвращает индекс первой строки, покрытой ячейкой. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Возвращает индекс первого столбца, покрытого ячейкой. |
| [getWidth()](#getWidth--) | Возвращает ширину ячейки. |
| [getHeight()](#getHeight--) | Возвращает высоту ячейки. |
| [getMinimalHeight()](#getMinimalHeight--) | Возвращает минимальную высоту ячейки. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает или задает левый отступ в TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Возвращает или задает левый отступ в TextFrame. |
| [getMarginRight()](#getMarginRight--) | Возвращает или задает правый отступ в TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Возвращает или задает правый отступ в TextFrame. |
| [getMarginTop()](#getMarginTop--) | Возвращает или задает верхний отступ в TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Возвращает или задает верхний отступ в TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Возвращает или задает нижний отступ в TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Возвращает или задает нижний отступ в TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Возвращает или задает тип вертикального текста. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Возвращает или задает тип вертикального текста. |
| [getTextAnchorType()](#getTextAnchorType--) | Возвращает или задает тип привязки текста. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Возвращает или задает тип привязки текста. |
| [getAnchorCenter()](#getAnchorCenter--) | Определяет, центрирован ли текстовый блок внутри ячейки. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Определяет, центрирован ли текстовый блок внутри ячейки. |
| [getFirstRow()](#getFirstRow--) | Получает первую строку ячейки. |
| [getFirstColumn()](#getFirstColumn--) | Получает первый столбец ячейки. |
| [getColSpan()](#getColSpan--) | Возвращает количество колонок сетки в таблице-родителе, которые должна охватывать текущая ячейка. |
| [getRowSpan()](#getRowSpan--) | Возвращает количество строк, которые охватывает объединённая ячейка. |
| [getTextFrame()](#getTextFrame--) | Возвращает текстовый фрейм ячейки. |
| [getTable()](#getTable--) | Возвращает объект Table-родителя для ячейки. |
| [isMergedCell()](#isMergedCell--) | Возвращает true, если ячейка объединена с любой соседней ячейкой, иначе false. |
| [getCellFormat()](#getCellFormat--) | Возвращает объект CellFormat, содержащий свойства форматирования этой ячейки. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Разделяет ячейку на две ячейки по индексу столбца. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Разделяет ячейку на две ячейки по индексу строки. |
| [splitByHeight(double height)](#splitByHeight-double-) | Разделяет ячейку по высоте. |
| [splitByWidth(double width)](#splitByWidth-double-) | Разделяет ячейку по ширине. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд ячейки. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию ячейки. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Возвращает расстояние от левой стороны таблицы до левой стороны ячейки. Только для чтения double.

**Возвращает:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Возвращает расстояние от верхней стороны таблицы до верхней стороны ячейки. Только для чтения double.

**Возвращает:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Возвращает индекс первой строки, покрытой ячейкой. Только для чтения int.

**Возвращает:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Возвращает индекс первого столбца, покрытого ячейкой. Только для чтения int.

**Возвращает:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Возвращает ширину ячейки. Только для чтения double.

**Возвращает:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Возвращает высоту ячейки. Только для чтения double.

**Возвращает:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Возвращает минимальную высоту ячейки. Это сумма минимальных высот всех строк, покрытых ячейкой. Только для чтения double.

**Возвращает:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Возвращает или задает левый отступ в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Возвращает или задает левый отступ в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Возвращает или задает правый отступ в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Возвращает или задает правый отступ в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Возвращает или задает верхний отступ в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Возвращает или задает верхний отступ в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Возвращает или задает нижний отступ в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Возвращает или задает нижний отступ в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Возвращает или задает тип вертикального текста. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращает:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Возвращает или задает тип вертикального текста. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Возвращает или задает тип привязки текста. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращает:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Возвращает или задает тип привязки текста. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Определяет, центрирован ли текстовый блок внутри ячейки. Чтение/запись boolean.

**Возвращает:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Определяет, центрирован ли текстовый блок внутри ячейки. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Получает первую строку ячейки. Только для чтения [IRow](../../com.aspose.slides/irow).

**Возвращает:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Получает первый столбец ячейки. Только для чтения [IColumn](../../com.aspose.slides/icolumn).

**Возвращает:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Возвращает количество колонок сетки в таблице-родителе, которые должна охватывать текущая ячейка. Это свойство позволяет ячейкам выглядеть как объединённые, охватывая вертикальные границы других ячеек. Только для чтения int.

**Возвращает:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Возвращает количество строк, которые охватывает объединённая ячейка. Используется совместно с атрибутом vMerge в других ячейках для указания начальной ячейки горизонтального объединения. Только для чтения int.

**Возвращает:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Возвращает текстовый фрейм ячейки. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Возвращает объект Table-родителя для ячейки. Только для чтения [ITable](../../com.aspose.slides/itable).

**Возвращает:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Возвращает true, если ячейка объединена с любой скорректированной ячейкой, иначе false. Только для чтения boolean.

**Возвращает:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Возвращает объект CellFormat, содержащий свойства форматирования этой ячейки. Только для чтения [ICellFormat](../../com.aspose.slides/icellformat).

**Возвращает:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Разделяет ячейку на две ячейки по индексу столбца.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс столбца. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Разделяет ячейку на две ячейки по индексу строки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс строки. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Разделяет ячейку по высоте.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| height | double | Высота строки. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Разделяет ячейку по ширине.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | double | Ширина колонки. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд ячейки. Только для чтения [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию ячейки. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject