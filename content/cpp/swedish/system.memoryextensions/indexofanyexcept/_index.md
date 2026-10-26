---
title: IndexOfAnyExcept()
second_title: Aspose.Slides för C++ API-referens
description: Hittar index för det första elementet som inte är lika med det angivna värdet i en ReadOnlySpan<T>
type: docs
weight: 170
url: /sv/system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) funktion


Hittar index för det första elementet som inte är lika med det angivna värdet i en ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spännet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spännet att söka i |
| value | const T\& | Värdet att utesluta från sökningen |

### Returvärde

Det nollbaserade indexet för det första icke-matchande elementet, eller -1 om det inte finns


## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funktion


Hittar index för det första elementet som inte är lika med någon av två angivna värden i en ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spännet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spännet att söka i |
| value0 | const T\& | Det första värdet att utesluta från sökningen |
| value1 | const T\& | Det andra värdet att utesluta från sökningen |

### Returvärde

Det nollbaserade indexet för det första icke-matchande elementet, eller -1 om det inte finns


## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funktion


Hittar index för det första elementet som inte är lika med något av tre angivna värden i en ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spännet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spännet att söka i |
| value0 | const T\& | Det första värdet att utesluta från sökningen |
| value1 | const T\& | Det andra värdet att utesluta från sökningen |
| value2 | const T\& | Det tredje värdet att utesluta från sökningen |

### Returvärde

Det nollbaserade indexet för det första icke-matchande elementet, eller -1 om det inte finns


## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) funktion


Hittar index för det första elementet som inte är lika med det angivna värdet i en Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spännet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Spännet att söka i |
| value | const T\& | Värdet att utesluta från sökningen |

### Returvärde

Det nollbaserade indexet för det första icke-matchande elementet, eller -1 om det inte finns


## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) funktion


Hittar index för det första elementet som inte är lika med någon av två angivna värden i en Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spännet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Spännet att söka i |
| value0 | const T\& | Det första värdet att utesluta från sökningen |
| value1 | const T\& | Det andra värdet att utesluta från sökningen |

### Returvärde

Det nollbaserade indexet för det första icke-matchande elementet, eller -1 om det inte finns


## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) funktion


Hittar index för det första elementet som inte är lika med något av tre angivna värden i en Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spännet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Spännet att söka i |
| value0 | const T\& | Det första värdet att utesluta från sökningen |
| value1 | const T\& | Det andra värdet att utesluta från sökningen |
| value2 | const T\& | Det tredje värdet att utesluta från sökningen |

### Returvärde

Det nollbaserade indexet för det första icke-matchande elementet, eller -1 om det inte finns


## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Hittar index för det första elementet som inte är lika med något värde i ett värdespan.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spännet att söka i |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spännet som innehåller värden att utesluta från sökningen |

### Returvärde

Det nollbaserade indexet för det första icke-matchande elementet, eller -1 om det inte finns


## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Hittar index för det första elementet som inte är lika med något värde i ett värdespan i en Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Spännet att söka i |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spännet som innehåller värden att utesluta från sökningen |

### Returvärde

Det nollbaserade indexet för det första icke-matchande elementet, eller -1 om det inte finns


## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)