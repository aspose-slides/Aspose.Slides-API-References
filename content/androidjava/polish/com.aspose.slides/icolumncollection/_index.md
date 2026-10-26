---
title: IColumnCollection
second_title: Aspose.Slides dla Androida - referencja Java API
description: Reprezentuje kolekcję kolumn w tabeli.
type: docs
url: /pl/com.aspose.slides/icolumncollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Reprezentuje kolekcję kolumn w tabeli.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca kolumnę o określonym indeksie. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Tworzy kopię określonego wiersza szablonu i wstawia ją na końcu tabeli. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Tworzy kopię określonej kolumny szablonu i wstawia ją na określonej pozycji w tabeli. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Usuwa kolumnę na określonej pozycji w tabeli. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Zwraca kolumnę o określonym indeksie. Tylko do odczytu [IColumn](../../com.aspose.slides/icolumn).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Tworzy kopię określonego wiersza szablonu i wstawia ją na końcu tabeli.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumna używana jako szablon. |
| withAttachedColumns | boolean | True aby skopiować także wszystkie kolumny dołączone do wiersza szablonu. |

**Returns:**
com.aspose.slides.IColumn[] - Dodane kolumny.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Tworzy kopię określonej kolumny szablonu i wstawia ją na określonej pozycji w tabeli.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks nowej kolumny. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumna używana jako szablon. |
| withAttachedColumns | boolean | True aby skopiować także wszystkie kolumny dołączone do kolumny szablonu. |

**Returns:**
com.aspose.slides.IColumn[] - Wstawione kolumny.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Usuwa kolumnę na określonej pozycji w tabeli.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | Indeks kolumny do usunięcia. |
| withAttachedRows | boolean | True aby usunąć także wszystkie dołączone kolumny. |