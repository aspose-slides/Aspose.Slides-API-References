---
title: IColumnCollection
second_title: Aspose.Slides dla Java API Reference
description: Reprezentuje kolekcję kolumn w tabeli.
type: docs
url: /pl/com.aspose.slides/icolumncollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Reprezentuje kolekcję kolumn w tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca kolumnę o podanym indeksie. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Tworzy kopię określonego wiersza szablonu i wstawia ją na koniec tabeli. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Tworzy kopię określonej kolumny szablonu i wstawia ją w określonej pozycji w tabeli. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Usuwa kolumnę w określonej pozycji z tabeli. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Zwraca kolumnę o podanym indeksie. Tylko do odczytu [IColumn](../../com.aspose.slides/icolumn).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Tworzy kopię określonego wiersza szablonu i wstawia ją na koniec tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumna używana jako szablon. |
| withAttachedColumns | boolean | True, aby skopiować również wszystkie kolumny dołączone do wiersza szablonu. |

**Zwraca:**
com.aspose.slides.IColumn[] - Dodane kolumny.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Tworzy kopię określonej kolumny szablonu i wstawia ją w określonej pozycji w tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowej kolumny. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumna używana jako szablon. |
| withAttachedColumns | boolean | True, aby skopiować również wszystkie kolumny dołączone do kolumny szablonu. |

**Zwraca:**
com.aspose.slides.IColumn[] - Wstawione kolumny.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Usuwa kolumnę w określonej pozycji z tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| firstColumnIndex | int | Indeks kolumny do usunięcia. |
| withAttachedRows | boolean | True, aby usunąć również wszystkie dołączone kolumny. |