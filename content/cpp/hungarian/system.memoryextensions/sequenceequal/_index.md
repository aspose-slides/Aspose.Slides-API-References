---
title: SequenceEqual()
second_title: Aspose.Slides C++ API referenciája
description: Megállapítja, hogy két ReadOnlySpan azonos elemeket tartalmaz-e ugyanabban a sorrendben.
type: docs
weight: 326
url: /hu/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megállapítja, hogy két ReadOnlySpan azonos elemeket tartalmaz-e ugyanabban a sorrendben.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az első span az összehasonlításhoz |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A második span az összehasonlításhoz |

### Visszatérési érték

true ha a spanek ugyanakkora hosszúak és minden elem egyenlő, false egyébként

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megállapítja, hogy egy [Span](../../system/span/) és egy [ReadOnlySpan](../../system/readonlyspan/) azonos elemeket tartalmaz-e ugyanabban a sorrendben.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A [Span](../../system/span/) az összehasonlításhoz |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A [ReadOnlySpan](../../system/readonlyspan/) az összehasonlításhoz |

### Visszatérési érték

true ha a spanek ugyanakkora hosszúak és minden elem egyenlő, false egyébként

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) függvény


Megállapítja, hogy két ReadOnlySpan egy egyedi összehasonlító használatával azonos elemeket tartalmaz-e.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanek elemeinek típusa |
| TComparer | Az összehasonlító objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az első span az összehasonlításhoz |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A második span az összehasonlításhoz |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Intelligens mutató az összehasonlító objektumra az elemek összehasonlításához |

### Visszatérési érték

true ha a spanek ugyanakkora hosszúak és az összehasonlító minden elemet egyenlőnek tekint, false egyébként

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) függvény


Megállapítja, hogy egy [Span](../../system/span/) és egy [ReadOnlySpan](../../system/readonlyspan/) egy egyedi összehasonlító használatával azonos elemeket tartalmaz-e.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanek elemeinek típusa |
| TComparer | Az összehasonlító objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A [Span](../../system/span/) az összehasonlításhoz |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A [ReadOnlySpan](../../system/readonlyspan/) az összehasonlításhoz |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Intelligens mutató az összehasonlító objektumra az elemek összehasonlításához |

### Visszatérési érték

true ha a spanek ugyanakkora hosszúak és az összehasonlító minden elemet egyenlőnek tekint, false egyébként

## Lásd még

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)