---
title: IVbaModuleCollection
second_title: Aspose.Slides dla Androida przy użyciu Java API
description: Reprezentuje kolekcję modułów projektu VBA.
type: docs
url: /pl/com.aspose.slides/ivbamodulecollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Reprezentuje kolekcję modułów projektu VBA.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Dodaje nowy pusty moduł do projektu VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Pobiera element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


Dodaje nowy pusty moduł do projektu VBA.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa modułu |

**Zwraca:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Dodany moduł.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Moduł do usunięcia z kolekcji. |