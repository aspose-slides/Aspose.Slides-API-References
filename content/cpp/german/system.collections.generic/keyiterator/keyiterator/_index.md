---
title: KeyIterator()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruktor.
type: docs
weight: 1
url: /de/system.collections.generic/keyiterator/keyiterator/
---
## KeyIterator::KeyIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) constructor


Konstruktor.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | Iterator zum Halten. |
| end | typename Dict::map_t::const_iterator\&& | Iterator zum Ende des Containers. |

## KeyIterator::KeyIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) constructor


Konstruktor.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | Iterator zum Halten. |
| end | const typename Dict::map_t::const_iterator\& | Iterator zum Ende des Containers. |

## KeyIterator::KeyIterator(KeyIterator\&&) constructor


Move-Konstruktor.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(KeyIterator &&other) noexcept
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [KeyIterator](../)\&& | Iterator, von dem Daten verschoben werden. |

## Siehe auch

* Klasse [KeyIterator](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)