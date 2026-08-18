---
title: ICell
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje komórkę w tabeli.
type: docs
url: /pl/com.aspose.slides/icell/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Reprezentuje komórkę w tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Zwraca odległość od lewej krawędzi tabeli do lewej krawędzi komórki. |
| [getOffsetY()](#getOffsetY--) | Zwraca odległość od górnej krawędzi tabeli do górnej krawędzi komórki. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Zwraca indeks pierwszego wiersza pokrywanego przez komórkę. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Zwraca indeks pierwszej kolumny pokrywanej przez komórkę. |
| [getWidth()](#getWidth--) | Zwraca szerokość komórki. |
| [getHeight()](#getHeight--) | Zwraca wysokość komórki. |
| [getMinimalHeight()](#getMinimalHeight--) | Zwraca minimalną wysokość komórki. |
| [getMarginLeft()](#getMarginLeft--) | Zwraca lub ustawia lewy margines w TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Zwraca lub ustawia lewy margines w TextFrame. |
| [getMarginRight()](#getMarginRight--) | Zwraca lub ustawia prawy margines w TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Zwraca lub ustawia prawy margines w TextFrame. |
| [getMarginTop()](#getMarginTop--) | Zwraca lub ustawia górny margines w TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Zwraca lub ustawia górny margines w TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Zwraca lub ustawia dolny margines w TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Zwraca lub ustawia dolny margines w TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Zwraca lub ustawia typ pionowego tekstu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Zwraca lub ustawia typ pionowego tekstu. |
| [getTextAnchorType()](#getTextAnchorType--) | Zwraca lub ustawia typ kotwiczenia tekstu. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Zwraca lub ustawia typ kotwiczenia tekstu. |
| [getAnchorCenter()](#getAnchorCenter--) | Określa, czy pole tekstowe jest wyśrodkowane w komórce. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Określa, czy pole tekstowe jest wyśrodkowane w komórce. |
| [getFirstColumn()](#getFirstColumn--) | Pobiera pierwszą kolumnę komórki. |
| [getFirstRow()](#getFirstRow--) | Pobiera pierwszy wiersz komórki. |
| [getColSpan()](#getColSpan--) | Zwraca liczbę kolumn siatki w siatce tabeli nadrzędnej, które mają być rozciągnięte przez bieżącą komórkę. |
| [getRowSpan()](#getRowSpan--) | Zwraca liczbę wierszy, które obejmuje scalona komórka. |
| [getTextFrame()](#getTextFrame--) | Zwraca ramkę tekstową komórki. |
| [getTable()](#getTable--) | Zwraca obiekt nadrzędnej tabeli dla komórki. |
| [isMergedCell()](#isMergedCell--) | Zwraca true, jeśli komórka jest scalona z jakąkolwiek dopasowaną komórką, w przeciwnym razie false. |
| [getCellFormat()](#getCellFormat--) | Zwraca obiekt CellFormat zawierający właściwości formatowania tej komórki. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Dzieli komórkę na dwie komórki według indeksu kolumny. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Dzieli komórkę na dwie komórki według indeksu wiersza. |
| [splitByHeight(double height)](#splitByHeight-double-) | Dzieli komórkę według wysokości. |
| [splitByWidth(double width)](#splitByWidth-double-) | Dzieli komórkę według szerokości. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Zwraca odległość od lewej krawędzi tabeli do lewej krawędzi komórki. Tylko do odczytu double.

**Zwraca:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Zwraca odległość od górnej krawędzi tabeli do górnej krawędzi komórki. Tylko do odczytu double.

**Zwraca:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Zwraca indeks pierwszego wiersza pokrywanego przez komórkę. Tylko do odczytu int.

**Zwraca:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Zwraca indeks pierwszej kolumny pokrywanej przez komórkę. Tylko do odczytu int.

**Zwraca:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Zwraca szerokość komórki. Tylko do odczytu double.

**Zwraca:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Zwraca wysokość komórki. Tylko do odczytu double.

**Zwraca:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Zwraca minimalną wysokość komórki. Jest to suma minimalnych wysokości wszystkich wierszy pokrywanych przez komórkę. Tylko do odczytu double.

**Zwraca:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Zwraca lub ustawia lewy margines w TextFrame. Do odczytu i zapisu double.

**Zwraca:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Zwraca lub ustawia lewy margines w TextFrame. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Zwraca lub ustawia prawy margines w TextFrame. Do odczytu i zapisu double.

**Zwraca:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Zwraca lub ustawia prawy margines w TextFrame. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Zwraca lub ustawia górny margines w TextFrame. Do odczytu i zapisu double.

**Zwraca:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Zwraca lub ustawia górny margines w TextFrame. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Zwraca lub ustawia dolny margines w TextFrame. Do odczytu i zapisu double.

**Zwraca:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Zwraca lub ustawia dolny margines w TextFrame. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Zwraca lub ustawia typ pionowego tekstu. Do odczytu i zapisu [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Zwraca:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Zwraca lub ustawia typ pionowego tekstu. Do odczytu i zapisu [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Zwraca lub ustawia typ kotwiczenia tekstu. Do odczytu i zapisu [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Zwraca lub ustawia typ kotwiczenia tekstu. Do odczytu i zapisu [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Określa, czy pole tekstowe jest wyśrodkowane w komórce. Do odczytu i zapisu boolean.

**Zwraca:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Określa, czy pole tekstowe jest wyśrodkowane w komórce. Do odczytu i zapisu boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Pobiera pierwszą kolumnę komórki. Tylko do odczytu [IColumn](../../com.aspose.slides/icolumn).

**Zwraca:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Pobiera pierwszy wiersz komórki. Tylko do odczytu [IRow](../../com.aspose.slides/irow).

**Zwraca:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Zwraca liczbę kolumn siatki w siatce tabeli nadrzędnej, które mają być rozciągnięte przez bieżącą komórkę. To właściwość pozwala komórkom wyglądać na połączone, gdy rozciągają pionowe granice innych komórek w tabeli. Tylko do odczytu int.

**Zwraca:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Zwraca liczbę wierszy, które obejmuje scalona komórka. Jest używana w połączeniu z atrybutem vMerge w innych komórkach w celu określenia początkowej komórki poziomego scalania. Tylko do odczytu int.

**Zwraca:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Zwraca ramkę tekstową komórki. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Zwraca obiekt nadrędnej tabeli dla komórki. Tylko do odczytu [ITable](../../com.aspose.slides/itable).

**Zwraca:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Zwraca true, jeśli komórka jest scalona z jakąkolwiek dopasowaną komórką, w przeciwnym razie false. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Zwraca obiekt CellFormat zawierający właściwości formatowania tej komórki. Tylko do odczytu [ICellFormat](../../com.aspose.slides/icellformat).

**Zwraca:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Dzieli komórkę na dwie komórki według indeksu kolumny.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks kolumny. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Dzieli komórkę na dwie komórki według indeksu wiersza.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks wiersza. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Dzieli komórkę według wysokości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| height | double | Wysokość wiersza. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Dzieli komórkę według szerokości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| width | double | Szerokość kolumny. |