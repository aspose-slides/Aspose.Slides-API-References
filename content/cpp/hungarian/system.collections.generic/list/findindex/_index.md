---
title: FindIndex()
second_title: Aspose.Slides C++ API hivatkozás
description: Megkeresi a meghatározott predikátumnak megfelelő elemet.
type: docs
weight: 404
url: /hu/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) metódus

Megkeresi a meghatározott predikátumnak megfelelő elemet.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Az elemek ellenőrzésére használt predikátum. |

### Visszatérési érték

[Index](../../../system/index/) az egyező elem indexe vagy -1, ha nem található.

## List::FindIndex(int, System::Predicate\<T\>) metódus

Megkeresi a meghatározott predikátumnak megfelelő elemet.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) a keresés kezdéséhez. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Az elemek ellenőrzésére használt predikátum. |

### Visszatérési érték

[Index](../../../system/index/) az egyező elem indexe vagy -1, ha nem található.

## List::FindIndex(int, int, System::Predicate\<T\>) metódus

Megkeresi a meghatározott predikátumnak megfelelő elemet.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) a keresés kezdéséhez. |
| count | int | A keresendő elemek száma. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Az elemek ellenőrzésére használt predikátum. |

### Visszatérési érték

[Index](../../../system/index/) az egyező elem indexe vagy -1, ha nem található.

## Lásd még

* Típusdefiníció [Predicate](../../../system/predicate/)
* Osztály [List](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)