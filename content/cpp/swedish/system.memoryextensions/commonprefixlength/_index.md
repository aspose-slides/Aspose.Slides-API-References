---
title: CommonPrefixLength()
second_title: Aspose.Slides för C++ API-referens
description: Hittar längden på det gemensamma prefixet mellan två intervall.
type: docs
weight: 27
url: /sv/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Hittar längden på det gemensamma prefixet mellan två intervall.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det första intervallet |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det andra intervallet |

### Returvärde

Antalet matchande element i början av båda intervallen

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Hittar längden på det gemensamma prefixet mellan ett skrivbart intervall och ett skrivskyddat intervall.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det skrivbara intervallet |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det skrivskyddade intervallet |

### Returvärde

Antalet matchande element i början av båda intervallen

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) funktion


Hittar längden på det gemensamma prefixet mellan två skrivbara intervall.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det första skrivbara intervallet |
| other | const [Span](../../system/span/)\<T\>\& | Det andra skrivbara intervallet |

### Returvärde

Antalet matchande element i början av båda intervallen

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funktion


Hittar längden på det gemensamma prefixet mellan två intervall med en anpassad likhetsjämförare.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallen |
| TEqualityComparer | Typen av likhetsjämförare |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det första intervallet |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det andra intervallet |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Den likhetsjämförare som ska användas för elementjämförelse |

### Returvärde

Antalet matchande element i början av båda intervallen

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funktion


Hittar längden på det gemensamma prefixet mellan ett skrivbart intervall och ett skrivskyddat intervall med en anpassad likhetsjämförare.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallen |
| TEqualityComparer | Typen av likhetsjämförare |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det skrivbara intervallet |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det skrivskyddade intervallet |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Den likhetsjämförare som ska användas för elementjämförelse |

### Returvärde

Antalet matchande element i början av båda intervallen

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funktion


Hittar längden på det gemensamma prefixet mellan två skrivbara intervall med en anpassad likhetsjämförare.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallen |
| TEqualityComparer | Typen av likhetsjämförare |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det första skrivbara intervallet |
| other | const [Span](../../system/span/)\<T\>\& | Det andra skrivbara intervallet |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Den likhetsjämförare som ska användas för elementjämförelse |

### Returvärde

Antalet matchande element i början av båda intervallen

## Se också

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)