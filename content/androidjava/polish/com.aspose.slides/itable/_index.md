---
title: ITable
second_title: Aspose.Slides dla Androida poprzez interfejs API Java
description: Reprezentuje tabelę na slajdzie.
type: docs
url: /pl/com.aspose.slides/itable/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Reprezentuje tabelę na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Zwraca komórkę w podanych indeksach kolumny i wiersza. |
| [getRows()](#getRows--) | Zwraca kolekcję wierszy. |
| [getColumns()](#getColumns--) | Zwraca kolekcję kolumn. |
| [getTableFormat()](#getTableFormat--) | Zwraca obiekt TableFormat zawierający właściwości formatowania tej tabeli. |
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
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Łączy sąsiednie komórki. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Zwraca komórkę w podanych indeksach kolumny i wiersza. Tylko do odczytu [ICell](../../com.aspose.slides/icell).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Zwraca:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Zwraca kolekcję wierszy. Tylko do odczytu [IRowCollection](../../com.aspose.slides/irowcollection).

**Zwraca:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Zwraca kolekcję kolumn. Tylko do odczytu [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Zwraca:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Zwraca obiekt TableFormat zawierający właściwości formatowania tej tabeli. Tylko do odczytu [ITableFormat](../../com.aspose.slides/itableformat).

**Zwraca:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Pobiera lub ustawia wbudowany styl tabeli. Odczyt/zapis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Zwraca:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Pobiera lub ustawia wbudowany styl tabeli. Odczyt/zapis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Określa, czy tabela ma kolejność czytania od prawej do lewej. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Określa, czy tabela ma kolejność czytania od prawej do lewej. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Łączy sąsiednie komórki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Komórka do połączenia. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Komórka do połączenia. |
| allowSplitting | boolean | True, aby zezwolić na dzielenie komórek. |

**Zwraca:**
[ICell](../../com.aspose.slides/icell) - scalona komórka.