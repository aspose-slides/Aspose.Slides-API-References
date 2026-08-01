---
title: EndsWith()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of een ReadOnlySpan<T> eindigt met een enkele waarde.
type: docs
weight: 131
url: /nl/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) functie


Bepaalt of een ReadOnlySpan<T> eindigt met een enkele waarde.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om te controleren |
| value | const T\& | De waarde om te controleren aan het einde van de span |

### Retourwaarde

true als de span eindigt met de waarde, false anders

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Bepaalt of een ReadOnlySpan<T> eindigt met een andere ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om te controleren |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om aan het einde van de doelspan te controleren |

### Retourwaarde

true als de span eindigt met de waardespan, false anders

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Bepaalt of een Span<T> eindigt met een ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span om te controleren |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om aan het einde van de doelspan te controleren |

### Retourwaarde

true als de span eindigt met de waardespan, false anders

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) functie


Bepaalt of een ReadOnlySpan<T> eindigt met een Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om te controleren |
| value | const [Span](../../system/span/)\<T\>\& | De span om aan het einde van de doelspan te controleren |

### Retourwaarde

true als de span eindigt met de waardespan, false anders

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) functie


Bepaalt of een Span<T> eindigt met een andere Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span om te controleren |
| value | const [Span](../../system/span/)\<T\>\& | De span om aan het einde van de doelspan te controleren |

### Retourwaarde

true als de span eindigt met de waardespan, false anders

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) functie


Bepaalt of een ReadOnlySpan<char16_t> eindigt met de opgegeven waarde met behulp van StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De span om te controleren |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De waarde om te controleren aan het einde van de span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Het te gebruiken stringvergelijkingstype |

### Retourwaarde

true als de span eindigt met de waarde, false anders

## Zie ook

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)