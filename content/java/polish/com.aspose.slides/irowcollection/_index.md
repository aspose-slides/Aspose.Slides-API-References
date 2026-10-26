---
title: IRowCollection
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje kolekcję wierszy tabeli.
type: docs
url: /pl/com.aspose.slides/irowcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Reprezentuje kolekcję wierszy tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Tworzy kopię określonego wiersza szablonu i wstawia ją na końcu tabeli. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Tworzy kopię określonego wiersza szablonu i wstawia ją na podanej pozycji w tabeli. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Usuwa wiersz na podanej pozycji z tabeli. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Pobiera element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Tworzy kopię określonego wiersza szablonu i wstawia ją na końcu tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Wiersz używany jako szablon. |
| withAttachedRows | boolean | True, aby skopiować również wszystkie wiersze dołączone do wiersza szablonu. |

**Zwraca:**
com.aspose.slides.IRow[] - Dodane wiersze.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Tworzy kopię określonego wiersza szablonu i wstawia ją na podanej pozycji w tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego wiersza. |
| templ | [IRow](../../com.aspose.slides/irow) | Wiersz używany jako szablon. |
| withAttachedRows | boolean | True, aby skopiować również wszystkie wiersze dołączone do wiersza szablonu. |

**Zwraca:**
com.aspose.slides.IRow[] - Wstawione wiersze.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Usuwa wiersz na podanej pozycji z tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| firstRowIndex | int | Indeks wiersza do usunięcia. |
| withAttachedRows | boolean | True, aby usunąć również wszystkie dołączone wiersze. |