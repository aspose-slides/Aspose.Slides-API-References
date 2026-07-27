---
title: DictionaryIterator()
second_title: Referência da API Aspose.Slides para C++
description: Construtor.
type: docs
weight: 1
url: /pt/system.collections.generic/dictionaryiterator/dictionaryiterator/
---
## DictionaryIterator::DictionaryIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) constructor


Construtor.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | Iterador a ser mantido. |
| end | typename Dict::map_t::const_iterator\&& | Iterador para o final do contêiner. |

## DictionaryIterator::DictionaryIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) constructor


Construtor.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | Iterador a ser mantido. |
| end | const typename Dict::map_t::const_iterator\& | Iterador para o final do contêiner. |

## DictionaryIterator::DictionaryIterator(DictionaryIterator\&&) constructor


Construtor de movimentação.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(DictionaryIterator &&other) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | [DictionaryIterator](../)\&& | Iterador de onde mover os dados. |

## Veja Também

* Classe [DictionaryIterator](../)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)