---
title: StartsWith()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of de span begint met de opgegeven waarde.
type: docs
weight: 352
url: /nl/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) functie


Controleert of de span begint met de opgegeven waarde.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om te controleren |
| value | const T\& | De waarde die aan het begin van de span moet worden gecontroleerd |

### Retourwaarde

true als de span begint met de waarde, false anders

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Controleert of de span begint met de opgegeven waardespan.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om te controleren |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span die waarden bevat die aan het begin moeten worden gecontroleerd |

### Retourwaarde

true als de span begint met de waardespan, false anders

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Controleert of de mutabele span begint met de opgegeven alleen-lezen waardespan.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De mutabele span om te controleren |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De alleen-lezen span die waarden bevat om te controleren |

### Retourwaarde

true als de span begint met de waardespan, false anders

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) functie


Controleert of de alleen-lezen span begint met de opgegeven mutabele waardespan.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De alleen-lezen span om te controleren |
| value | const [Span](../../system/span/)\<T\>\& | De mutabele span die waarden bevat om te controleren |

### Retourwaarde

true als de span begint met de waardespan, false anders

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) functie


Controleert of de teken-span begint met de opgegeven waardespan met behulp van tekenreeksvergelijking.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De te verifieren teken-span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De teken-span die waarden bevat om te controleren |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Het type tekenreeksvergelijking dat moet worden uitgevoerd |

### Retourwaarde

true als de span begint met de waardespan, false anders

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) functie


Controleert of een tekenreeks-span begint met de opgegeven tekenreeks-array.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | De te controleren tekenreeks-span |
| val | const char16_t * | De tekenreeks-array die aan het begin moet worden gecontroleerd |

### Retourwaarde

true als de span begint met de tekenreeks-array, false anders

## Zie ook

* Enum [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Klasse [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)