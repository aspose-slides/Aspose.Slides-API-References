---
title: KeyIterator()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur.
type: docs
weight: 1
url: /fr/system.collections.generic/keyiterator/keyiterator/
---
## KeyIterator::KeyIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) constructeur

Constructeur.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | Itérateur à conserver. |
| end | typename Dict::map_t::const_iterator\&& | Itérateur vers la fin du conteneur. |

## KeyIterator::KeyIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) constructeur

Constructeur.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | Itérateur à conserver. |
| end | const typename Dict::map_t::const_iterator\& | Itérateur vers la fin du conteneur. |

## KeyIterator::KeyIterator(KeyIterator\&&) constructeur

Constructeur de déplacement.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(KeyIterator &&other) noexcept
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| other | [KeyIterator](../)\&& | Itérateur dont les données seront déplacées. |

## Voir aussi

* Class [KeyIterator](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)