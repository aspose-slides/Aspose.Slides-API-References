---
title: IColorOperationCollection
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje kolekcję operacji transformacji kolorów.
type: docs
url: /pl/com.aspose.slides/icoloroperationcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Reprezentuje kolekcję operacji transformacji kolorów.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca lub ustawia operację o podanym indeksie. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Zwraca lub ustawia operację o podanym indeksie. |
| [add(int operation, float parameter)](#add-int-float-) | Dodaje nową operację na końcu kolekcji. |
| [add(int operation)](#add-int-) | Dodaje nową operację na końcu kolekcji. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Wstawia nową operację do kolekcji. |
| [insert(int position, int operation)](#insert-int-int-) | Wstawia nową operację do kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa operację koloru z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie operacje koloru. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```


Zwraca lub ustawia operację o podanym indeksie. Odczyt/zapis [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```


Zwraca lub ustawia operację o podanym indeksie. Odczyt/zapis [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```


Dodaje nową operację na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operation | int | Typ operacji. |
| parameter | float | Parametr operacji. |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Dodana operacja.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```


Dodaje nową operację na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operation | int | Typ operacji. |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Dodana operacja.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```


Wstawia nową operację do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | int | Indeks, pod którym operacja zostanie wstawiona. |
| operation | int | Typ operacji. |
| parameter | float | Parametr operacji. |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Wstawiona operacja.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```


Wstawia nową operację do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | int | Indeks, pod którym operacja zostanie wstawiona. |
| operation | int | Typ operacji. |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Wstawiona operacja.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa operację koloru z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks operacji koloru do usunięcia. |

### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie operacje koloru.