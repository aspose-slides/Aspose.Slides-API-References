---
title: CopyTo()
second_title: Aspose.Slides pro C++ API Reference
description: Kopíruje prvky seznamu do existujících prvků pole.
type: docs
weight: 209
url: /cs/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) metoda


Kopíruje prvky seznamu do existujících prvků pole.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Cílové pole. |
| arrayIndex | int | Index počátečního prvku v cílovém poli. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) metoda


Kopíruje všechny prvky do existujících prvků pole.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) k kopírování prvků do. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) metoda


Kopíruje prvky počínaje zadaným indexem do existujících prvků pole.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index (0-based) prvku v seznamu reprezentovaném aktuálním objektem, odkud začít kopírovat |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) k kopírování prvků do. |
| arrayIndex | int | Počáteční pozice v cílovém poli. |
| count | int | Počet prvků k kopírování. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [List](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)