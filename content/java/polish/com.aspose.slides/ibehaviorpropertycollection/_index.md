---
title: IBehaviorPropertyCollection
second_title: Referencja API Aspose.Slides dla języka Java
description: Reprezentuje właściwości czasowe zachowania efektu.
type: docs
url: /pl/com.aspose.slides/ibehaviorpropertycollection/
---
**Wszystkie implementowane interfejsy:**
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
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Wstawia nową właściwość (z określoną wartością właściwości) do kolekcji pod podanym indeksem. |
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
int - Indeks właściwości o podanej wartości
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Wstawia nową właściwość (z określoną wartością właściwości) do kolekcji pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks, pod którym ma być wstawiona nowa właściwość. |
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
boolean - Prawda, jeśli właściwość została usunięta pomyślnie boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | Wartość właściwości do zlokalizowania w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true jeśli propertyValue zostanie znaleziona w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.