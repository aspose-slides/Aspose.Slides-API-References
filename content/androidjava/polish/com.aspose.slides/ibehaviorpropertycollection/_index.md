---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje właściwości czasowe zachowania efektu.
type: docs
url: /pl/com.aspose.slides/ibehaviorpropertycollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Reprezentuje właściwości czasowe zachowania efektu.
## Metody

| Metoda | Opis |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Dodaje nową właściwość do kolekcji. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Określa indeks określonego elementu na podstawie wartości właściwości w liście. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Wstawia nową właściwość (z określoną wartością właściwości) do kolekcji pod określonym indeksem. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Usuwa określoną właściwość z kolekcji. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```


Dodaje nową właściwość do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | Wartość właściwości do dodania. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```


Określa indeks określonego elementu na podstawie wartości właściwości w liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | wartość właściwości |

**Zwraca:**
int - Indeks właściwości o określonej wartości
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```


Wstawia nową właściwość (z określoną wartością właściwości) do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks, w którym nowa właściwość ma zostać wstawiona. |
| propertyValue | java.lang.String | Wartość właściwości do dodania. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```


Usuwa określoną właściwość z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | Wartość właściwości do usunięcia. |

**Zwraca:**
boolean - true jeśli właściwość została pomyślnie usunięta boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```


Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | Wartość właściwości do wyszukania w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true, jeśli propertyValue zostanie znaleziona w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.