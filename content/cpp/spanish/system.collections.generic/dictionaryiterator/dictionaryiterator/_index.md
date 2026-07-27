---
title: DictionaryIterator()
second_title: Referencia de la API de Aspose.Slides para C++
description: Constructor.
type: docs
weight: 1
url: /es/system.collections.generic/dictionaryiterator/dictionaryiterator/
---
## DictionaryIterator::DictionaryIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) constructor

Constructor.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | Iterador a mantener. |
| end | typename Dict::map_t::const_iterator\&& | Iterador al final del contenedor. |

## DictionaryIterator::DictionaryIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) constructor

Constructor.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | Iterador a mantener. |
| end | const typename Dict::map_t::const_iterator\& | Iterador al final del contenedor. |

## DictionaryIterator::DictionaryIterator(DictionaryIterator\&&) constructor

Constructor de movimiento.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(DictionaryIterator &&other) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [DictionaryIterator](../)\&& | Iterador del cual mover los datos. |

## Ver también

* Clase [DictionaryIterator](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)