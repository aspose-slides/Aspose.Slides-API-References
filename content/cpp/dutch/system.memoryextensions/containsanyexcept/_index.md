---
title: ContainsAnyExcept()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een read-only span een element bevat dat niet overeenkomt met drie opgegeven waarden.
type: docs
weight: 66
url: /nl/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) functie

Controleert of een read-only span een element bevat dat niet overeenkomt met drie opgegeven waarden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value0 | const T\& | De eerste waarde die uitgesloten moet worden |
| value1 | const T\& | De tweede waarde die uitgesloten moet worden |
| value2 | const T\& | De derde waarde die uitgesloten moet worden |

### Retourwaarde

true als een element dat verschilt van de opgegeven waarden wordt gevonden, anders false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) functie

Controleert of een mutable span een element bevat dat niet overeenkomt met drie opgegeven waarden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De mutable span waarin gezocht wordt |
| value0 | const T\& | De eerste waarde die uitgesloten moet worden |
| value1 | const T\& | De tweede waarde die uitgesloten moet worden |
| value2 | const T\& | De derde waarde die uitgesloten moet worden |

### Retourwaarde

true als een element dat verschilt van de opgegeven waarden wordt gevonden, anders false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) functie

Controleert of een read-only span een element bevat dat niet overeenkomt met twee opgegeven waarden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value0 | const T\& | De eerste waarde die uitgesloten moet worden |
| value1 | const T\& | De tweede waarde die uitgesloten moet worden |

### Retourwaarde

true als een element dat verschilt van de opgegeven waarden wordt gevonden, anders false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) functie

Controleert of een mutable span een element bevat dat niet overeenkomt met twee opgegeven waarden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De mutable span waarin gezocht wordt |
| value0 | const T\& | De eerste waarde die uitgesloten moet worden |
| value1 | const T\& | De tweede waarde die uitgesloten moet worden |

### Retourwaarde

true als een element dat verschilt van de opgegeven waarden wordt gevonden, anders false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) functie

Controleert of een read-only span een element bevat dat niet overeenkomt met de opgegeven waarde.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value | const T\& | De waarde die uitgesloten moet worden |

### Retourwaarde

true als een element dat verschilt van de opgegeven waarde wordt gevonden, anders false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) functie

Controleert of een mutable span een element bevat dat niet overeenkomt met de opgegeven waarde.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De mutable span waarin gezocht wordt |
| value | const T\& | De waarde die uitgesloten moet worden |

### Retourwaarde

true als een element dat verschilt van de opgegeven waarde wordt gevonden, anders false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Controleert of een read-only span een element bevat dat niet voorkomt in een andere span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de spans |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span met waarden die uitgesloten moeten worden |

### Retourwaarde

true als een element dat niet in values voorkomt wordt gevonden, anders false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Controleert of een mutable span een element bevat dat niet voorkomt in een read-only span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de spans |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De mutable span waarin gezocht wordt |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De read-only span met waarden die uitgesloten moeten worden |

### Retourwaarde

true als een element dat niet in values voorkomt wordt gevonden, anders false

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)