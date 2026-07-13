---
title: BehaviorPropertyCollection
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje właściwości czasu dla zachowania efektu.
type: docs
url: /pl/com.aspose.slides/behaviorpropertycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Reprezentuje właściwości czasu dla zachowania efektu.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę właściwości przechowywanych w kolekcji. |
| [isReadOnly()](#isReadOnly--) | Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Dodaje nową właściwość do kolekcji. |
| [add(String propertyValue)](#add-java.lang.String-) | Dodaje nową właściwość do kolekcji. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Określa indeks określonego elementu na liście. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Określa indeks określonego elementu według wartości właściwości na liście. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Wstawia nową właściwość do kolekcji pod określonym indeksem. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Wstawia nową właściwość (z określoną wartością) do kolekcji pod określonym indeksem. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Usuwa określoną właściwość z kolekcji. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Usuwa określoną właściwość z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa właściwość pod określonym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie właściwości z kolekcji. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
| [get_Item(int index)](#get-Item-int-) | Zwraca właściwość pod określonym indeksem. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Ustawia właściwość pod określonym indeksem. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę właściwości przechowywanych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. Tylko do odczytu boolean.

**Zwraca:**
boolean - true jeśli [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu; w przeciwnym razie false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Dodaje nową właściwość do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Właściwość do dodania. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Dodaje nową właściwość do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | Wartość właściwości do dodania. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Określa indeks określonego elementu na liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Obiekt do znalezienia na liście. |

**Zwraca:**
int - Indeks elementu, jeśli został znaleziony; w przeciwnym razie -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Określa indeks określonego elementu według wartości właściwości na liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | wartość właściwości |

**Zwraca:**
int - Indeks właściwości o podanej wartości
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Wstawia nową właściwość do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks, pod którym ma być wstawiona nowa właściwość. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Właściwość do dodania. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Wstawia nową właściwość (z określoną wartością) do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks, pod którym ma być wstawiona nowa właściwość. |
| propertyValue | java.lang.String | Wartość właściwości do dodania. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Jednowymiarowa tablica będąca miejscem docelowym dla elementów kopiowanych z [IGenericCollection](../../com.aspose.slides/igenericcollection). Tablica musi mieć indeksowanie zerowe. |
| arrayIndex | int | Zerowy indeks w tablicy, od którego rozpoczyna się kopiowanie. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Usuwa określoną właściwość z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Właściwość do usunięcia. |

**Zwraca:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Usuwa określoną właściwość z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | Wartość właściwości do usunięcia. |

**Zwraca:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa właściwość pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks właściwości, która ma zostać usunięta. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie właściwości z kolekcji.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Właściwość do zlokalizowania w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true jeśli element zostanie znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | Wartość właściwości do zlokalizowania w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true jeśli propertyValue zostanie znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Zwraca właściwość pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks właściwości do zwrócenia. |

**Zwraca:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Właściwość zachowania animacji.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Ustawia właściwość pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks właściwości do zwrócenia. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - IGenericEnumerator, który można używać do iteracji po kolekcji.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Zwraca:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Zwraca:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Zwraca:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - java.util.Iterator dla całej kolekcji.