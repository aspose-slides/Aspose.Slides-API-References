---
title: Table
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje tabelę na slajdzie.
type: docs
url: /pl/com.aspose.slides/table/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Reprezentuje tabelę na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Zwraca komórkę o określonych indeksach kolumny i wiersza. |
| [getRows()](#getRows--) | Zwraca kolekcję wierszy. |
| [getColumns()](#getColumns--) | Zwraca kolekcję kolumn. |
| [getTableFormat()](#getTableFormat--) | Zwraca obiekt TableFormat zawierający właściwości formatowania tej tabeli. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Łączy sąsiednie komórki. |
| [getStylePreset()](#getStylePreset--) | Pobiera lub ustawia wbudowany styl tabeli. |
| [setStylePreset(int value)](#setStylePreset-int-) | Pobiera lub ustawia wbudowany styl tabeli. |
| [getRightToLeft()](#getRightToLeft--) | Określa, czy tabela ma kolejność czytania od prawej do lewej. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Określa, czy tabela ma kolejność czytania od prawej do lewej. |
| [getFirstRow()](#getFirstRow--) | Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. |
| [getFirstCol()](#getFirstCol--) | Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. |
| [getLastRow()](#getLastRow--) | Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. |
| [getLastCol()](#getLastCol--) | Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. |
| [getVerticalBanding()](#getVerticalBanding--) | Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ustawia określone właściwości formatu części dla wszystkich fragmentów komórek tabeli. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ustawia określone właściwości formatu akapitu dla wszystkich akapitów komórek tabeli. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ustawia określone właściwości formatu ramki tekstowej dla wszystkich ramek tekstowych komórek tabeli. |
| [getFillFormat()](#getFillFormat--) | Zwraca obiekt TableFormat.FillFormat zawierający formatowanie wypełnienia dla tabeli. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Zwraca komórkę o określonych indeksach kolumny i wiersza. Tylko do odczytu [Cell](../../com.aspose.slides/cell).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Zwraca:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Zwraca kolekcję wierszy. Tylko do odczytu [IRowCollection](../../com.aspose.slides/irowcollection).

**Zwraca:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Zwraca kolekcję kolumn. Tylko do odczytu [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Zwraca:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Zwraca obiekt TableFormat zawierający właściwości formatowania tej tabeli. Tylko do odczytu [ITableFormat](../../com.aspose.slides/itableformat).

**Zwraca:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Łączy sąsiednie komórki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Komórka do scalenia. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Komórka do scalenia. |
| allowSplitting | boolean | True, aby zezwolić na rozdzielanie komórek. |

**Zwraca:**
[ICell](../../com.aspose.slides/icell) - Połączona komórka.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Pobiera lub ustawia wbudowany styl tabeli. Odczyt/zapis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Zwraca:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Pobiera lub ustawia wbudowany styl tabeli. Odczyt/zapis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Określa, czy tabela ma kolejność czytania od prawej do lewej. Odczyt/zapis  boolean .

**Zwraca:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Określa, czy tabela ma kolejność czytania od prawej do lewej. Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Odczyt/zapis  boolean .

**Zwraca:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Odczyt/zapis  boolean .

**Zwraca:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Odczyt/zapis  boolean .

**Zwraca:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Odczyt/zapis  boolean .

**Zwraca:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. Odczyt/zapis  boolean .

**Zwraca:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. Odczyt/zapis  boolean .

**Zwraca:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Ustawia określone właściwości formatu części dla wszystkich fragmentów komórek tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Obiekt IPortionFormat z ustawionymi niezbędnymi właściwościami. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Ustawia określone właściwości formatu akapitu dla wszystkich akapitów komórek tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Obiekt IParagraphFormat z ustawionymi niezbędnymi właściwościami. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Ustawia określone właściwości formatu ramki tekstowej dla wszystkich ramek tekstowych komórek tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Obiekt ITextFrameFormat z ustawionymi niezbędnymi właściwościami. |
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Zwraca obiekt TableFormat.FillFormat zawierający formatowanie wypełnienia dla tabeli. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)