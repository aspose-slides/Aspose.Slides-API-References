---
title: Cell
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje komórkę tabeli.
type: docs
url: /pl/com.aspose.slides/cell/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Reprezentuje komórkę tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Zwraca odległość od lewej strony tabeli do lewej strony komórki. |
| [getOffsetY()](#getOffsetY--) | Zwraca odległość od górnej strony tabeli do górnej strony komórki. |
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
| [getTextAnchorType()](#getTextAnchorType--) | Zwraca lub ustawia typ kotwicy tekstu. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Zwraca lub ustawia typ kotwicy tekstu. |
| [getAnchorCenter()](#getAnchorCenter--) | Określa, czy pole tekstowe jest wyśrodkowane wewnątrz komórki. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Określa, czy pole tekstowe jest wyśrodkowane wewnątrz komórki. |
| [getFirstRow()](#getFirstRow--) | Pobiera pierwszy wiersz komórki. |
| [getFirstColumn()](#getFirstColumn--) | Pobiera pierwszą kolumnę komórki. |
| [getColSpan()](#getColSpan--) | Zwraca liczbę kolumn siatki w siatce tabeli nadrzędnej, które mają być rozciągnięte przez bieżącą komórkę. |
| [getRowSpan()](#getRowSpan--) | Zwraca liczbę wierszy, które zajmuje połączona komórka. |
| [getTextFrame()](#getTextFrame--) | Zwraca ramkę tekstową komórki. |
| [getTable()](#getTable--) | Zwraca obiekt nadrzędnej tabeli dla komórki. |
| [isMergedCell()](#isMergedCell--) | Zwraca true, jeśli komórka jest połączona z dowolną dostosowaną komórką, w przeciwnym razie false. |
| [getCellFormat()](#getCellFormat--) | Zwraca obiekt CellFormat zawierający właściwości formatowania tej komórki. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Dzieli komórkę na dwie komórki według indeksu kolumny. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Dzieli komórkę na dwie komórki według indeksu wiersza. |
| [splitByHeight(double height)](#splitByHeight-double-) | Dzieli komórkę według wysokości. |
| [splitByWidth(double width)](#splitByWidth-double-) | Dzieli komórkę według szerokości. |
| [getSlide()](#getSlide--) | Zwraca nadrzędny slajd komórki. |
| [getPresentation()](#getPresentation--) | Zwraca nadrzędną prezentację komórki. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Zwraca odległość od lewej strony tabeli do lewej strony komórki. Tylko do odczytu double.

**Zwraca:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Zwraca odległość od górnej strony tabeli do górnej strony komórki. Tylko do odczytu double.

**Zwraca:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Zwraca indeks pierwszego wiersza pokrywanego przez komórkę. Tylko do odczytu int.

**Zwraca:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Zwraca indeks pierwszej kolumny pokrywanej przez komórkę. Tylko do odczytu int.

**Zwraca:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Zwraca szerokość komórki. Tylko do odczytu double.

**Zwraca:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Zwraca wysokość komórki. Tylko do odczytu double.

**Zwraca:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Zwraca minimalną wysokość komórki. Jest to suma minimalnych wysokości wszystkich wierszy pokrywanych przez komórkę. Tylko do odczytu double.

**Zwraca:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Zwraca lub ustawia lewy margines w TextFrame. Odczyt/zapis double.

**Zwraca:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Zwraca lub ustawia lewy margines w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Zwraca lub ustawia prawy margines w TextFrame. Odczyt/zapis double.

**Zwraca:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Zwraca lub ustawia prawy margines w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Zwraca lub ustawia górny margines w TextFrame. Odczyt/zapis double.

**Zwraca:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Zwraca lub ustawia górny margines w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Zwraca lub ustawia dolny margines w TextFrame. Odczyt/zapis double.

**Zwraca:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Zwraca lub ustawia dolny margines w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Zwraca lub ustawia typ pionowego tekstu. Odczyt/zapis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Zwraca:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Zwraca lub ustawia typ pionowego tekstu. Odczyt/zapis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Zwraca lub ustawia typ kotwicy tekstu. Odczyt/zapis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Zwraca lub ustawia typ kotwicy tekstu. Odczyt/zapis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Określa, czy pole tekstowe jest wyśrodkowane wewnątrz komórki. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Określa, czy pole tekstowe jest wyśrodkowane wewnątrz komórki. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Pobiera pierwszy wiersz komórki. Tylko do odczytu [IRow](../../com.aspose.slides/irow).

**Zwraca:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Pobiera pierwszą kolumnę komórki. Tylko do odczytu [IColumn](../../com.aspose.slides/icolumn).

**Zwraca:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Zwraca liczbę kolumn siatki w siatce tabeli nadrzędnej, które mają być rozciągnięte przez bieżącą komórkę. Ta właściwość pozwala komórkom wyglądać jak połączone, ponieważ rozciągają pionowe granice innych komórek w tabeli. Tylko do odczytu int.

**Zwraca:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Zwraca liczbę wierszy, które zajmuje połączona komórka. Jest to używane w połączeniu z atrybutem vMerge w innych komórkach w celu określenia komórki początkowej poziomego łączenia. Tylko do odczytu int.

**Zwraca:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Zwraca ramkę tekstową komórki. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Zwraca obiekt nadrzędnej tabeli dla komórki. Tylko do odczytu [ITable](../../com.aspose.slides/itable).

**Zwraca:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Zwraca true, jeśli komórka jest połączona z dowolną dostosowaną komórką, w przeciwnym razie false. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Zwraca obiekt CellFormat zawierający właściwości formatowania tej komórki. Tylko do odczytu [ICellFormat](../../com.aspose.slides/icellformat).

**Zwraca:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Dzieli komórkę na dwie komórki według indeksu kolumny.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks kolumny. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Dzieli komórkę na dwie komórki według indeksu wiersza.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks wiersza. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Dzieli komórkę według wysokości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| height | double | Wysokość wiersza. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Dzieli komórkę według szerokości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| width | double | Szerokość kolumny. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca nadrzędny slajd komórki. Tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca nadrzędną prezentację komórki. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject