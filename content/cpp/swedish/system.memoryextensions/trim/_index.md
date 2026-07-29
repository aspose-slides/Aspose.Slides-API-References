---
title: Trim()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort det angivna elementet från båda ändarna av ett typat spann.
type: docs
weight: 365
url: /sv/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) funktion


Tar bort det angivna elementet från båda ändarna av ett typat spann.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet att trimma |
| trimElement | T | Elementet att trimma |

### Returvärde

Ett nytt spann med det angivna elementet borttaget från båda ändarna

## System::MemoryExtensions::Trim(Span\<T\>\&, T) funktion


Tar bort det angivna elementet från båda ändarna av ett skrivbart typat spann.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Det skrivbara spannet att trimma |
| trimElement | T | Elementet att trimma |

### Returvärde

Ett nytt spann med det angivna elementet borttaget från båda ändarna

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Tar bort de angivna elementen från båda ändarna av ett typat spann.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet att trimma |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elementen att trimma |

### Returvärde

Ett nytt spann med de angivna elementen borttagna från båda ändarna

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Tar bort de angivna elementen från båda ändarna av ett skrivbart typat spann.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Det skrivbara spannet att trimma |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elementen att trimma |

### Returvärde

Ett nytt spann med de angivna elementen borttagna från båda ändarna

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) funktion


Tar bort blankstegstecken från båda ändarna av ett teckenspann.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Teckenspannet att trimma |

### Returvärde

Ett nytt spann med blanksteg borttagna från båda ändarna

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) funktion


Tar bort blankstegstecken från båda ändarna av ett skrivbart teckenspann.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Det skrivbara teckenspannet att trimma |

### Returvärde

Ett nytt spann med blanksteg borttagna från båda ändarna

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)