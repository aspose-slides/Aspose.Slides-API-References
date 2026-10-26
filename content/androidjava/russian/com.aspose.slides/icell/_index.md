---
title: ICell
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет ячейку в таблице.
type: docs
url: /ru/com.aspose.slides/icell/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Представляет ячейку в таблице.
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
| [getFirstColumn()](#getFirstColumn--) | Получает первый столбец ячейки. |
| [getFirstRow()](#getFirstRow--) | Получает первую строку ячейки. |
| [getColSpan()](#getColSpan--) | Возвращает количество колонок сетки в таблице-родителе, которое должно покрываться текущей ячейкой. |
| [getRowSpan()](#getRowSpan--) | Возвращает количество строк, охватываемых объединённой ячейкой. |
| [getTextFrame()](#getTextFrame--) | Возвращает текстовый фрейм ячейки. |
| [getTable()](#getTable--) | Возвращает объект Table-родителя для ячейки. |
| [isMergedCell()](#isMergedCell--) | Возвращает true, если ячейка объединена с любой смежной ячейкой, иначе false. |
| [getCellFormat()](#getCellFormat--) | Возвращает объект CellFormat, содержащий свойства форматирования для этой ячейки. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Разделяет ячейку на две ячейки по индексу столбца. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Разделяет ячейку на две ячейки по индексу строки. |
| [splitByHeight(double height)](#splitByHeight-double-) | Разделяет ячейку по высоте. |
| [splitByWidth(double width)](#splitByWidth-double-) | Разделяет ячейку по ширине. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```


Возвращает расстояние от левой стороны таблицы до левой стороны ячейки. Только для чтения double.

**Возвращает:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```


Возвращает расстояние от верхней стороны таблицы до верхней стороны ячейки. Только для чтения double.

**Возвращает:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```


Возвращает индекс первой строки, покрытой ячейкой. Только для чтения int.

**Возвращает:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```


Возвращает индекс первого столбца, покрытого ячейкой. Только для чтения int.

**Возвращает:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Возвращает ширину ячейки. Только для чтения double.

**Возвращает:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Возвращает высоту ячейки. Только для чтения double.

**Возвращает:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Возвращает минимальную высоту ячейки. Это сумма минимальных высот всех строк, покрываемых ячейкой. Только для чтения double.

**Возвращает:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Возвращает или задает левый отступ в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Возвращает или задает левый отступ в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Возвращает или задает правый отступ в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Возвращает или задает правый отступ в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Возвращает или задает верхний отступ в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Возвращает или задает верхний отступ в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Возвращает или задает нижний отступ в TextFrame. Чтение/запись double.

**Возвращает:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Возвращает или задает нижний отступ в TextFrame. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Возвращает или задает тип вертикального текста. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращает:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Возвращает или задает тип вертикального текста. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```


Возвращает или задает тип привязки текста. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращает:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```


Возвращает или задает тип привязки текста. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```


Определяет, центрирован ли текстовый блок внутри ячейки. Чтение/запись boolean.

**Возвращает:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```


Определяет, центрирован ли текстовый блок внутри ячейки. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```


Получает первый столбец ячейки. Только для чтения [IColumn](../../com.aspose.slides/icolumn).

**Возвращает:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```


Получает первую строку ячейки. Только для чтения [IRow](../../com.aspose.slides/irow).

**Возвращает:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```


Возвращает количество колонок сетки в таблице-родителе, которое должно покрываться текущей ячейкой. Это свойство позволяет ячейкам выглядеть как объединённые, поскольку они охватывают вертикальные границы других ячеек в таблице. Только для чтения int.

**Возвращает:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```


Возвращает количество строк, охватываемых объединённой ячейкой. Это используется совместно с атрибутом vMerge в других ячейках для указания начальной ячейки горизонтального объединения. Только для чтения int.

**Возвращает:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Возвращает текстовый фрейм ячейки. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```


Возвращает объект Table-родителя для ячейки. Только для чтения [ITable](../../com.aspose.slides/itable).

**Возвращает:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```


Возвращает true, если ячейка объединена с любой смежной ячейкой, иначе false. Только для чтения boolean.

**Возвращает:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```


Возвращает объект CellFormat, содержащий свойства форматирования для этой ячейки. Только для чтения [ICellFormat](../../com.aspose.slides/icellformat).

**Возвращает:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```


Разделяет ячейку на две ячейки по индексу столбца.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс столбца. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```


Разделяет ячейку на две ячейки по индексу строки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс строки. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```


Разделяет ячейку по высоте.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| height | double | Высота строки. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```


Разделяет ячейку по ширине.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | double | Ширина столбца. |