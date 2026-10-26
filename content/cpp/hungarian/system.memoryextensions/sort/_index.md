---
title: Sort()
second_title: Aspose.Slides C++ API referencia
description: Rendezi a Span-t egy egyéni összehasonlítóval.
type: docs
weight: 339
url: /hu/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) függvény


Rendez egy [Span](../../system/span/) egyéni összehasonlító használatával.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |
| TComparer | Az összehasonlító objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A rendezendő span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Intelligens mutató az összehasonlító objektumra az elemek összehasonlításához |

## System::MemoryExtensions::Sort(Span\<T\>\&) függvény


Rendez egy [Span](../../system/span/) alapértelmezett összehasonlítással.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | A rendezendő span |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) függvény


Rendez kulcs-érték párokat egyéni összehasonlítóval (a kulcsok és az értékek együtt rendezve).

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |
| TComparer | Az összehasonlító objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A rendezendő kulcsok spanja |
| values | [Span](../../system/span/)\<TValue\>\& | A rendezendő értékek spanja (a kulcsokkal történő megfeleltetés megőrzésével) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Intelligens mutató az összehasonlító objektumra a kulcsok összehasonlításához |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) függvény


Rendez kulcs-érték párokat egy összehasonlítási delegáttal.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A rendezendő kulcsok spanja |
| values | [Span](../../system/span/)\<TValue\>\& | A rendezendő értékek spanja |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegát a kulcsok összehasonlításához |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) függvény


Rendez kulcs-érték párokat alapértelmezett összehasonlítással.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A rendezendő kulcsok spanja |
| values | [Span](../../system/span/)\<TValue\>\& | A rendezendő értékek spanja |

## Lásd még

* Typedef [SharedPtr](../../system/sharedptr/)
* Osztály [Span](../../system/span/)
* Osztály [Comparison](../../system/comparison/)
* Névtér [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)