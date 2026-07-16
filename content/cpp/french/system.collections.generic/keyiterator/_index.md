---
title: KeyIterator
second_title: Aspose.Slides pour la référence API C++
description: Itérateur de dictionnaire qui fournit un accès aux clés.
type: docs
weight: 365
url: /fr/system.collections.generic/keyiterator/
---
## KeyIterator classe

[Dictionary](../dictionary/) itérateur qui fournit un accès aux clés.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |

## Méthodes

| Méthode | Description |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Clone l'itérateur actuel. |
| void [DecrementIterator](./decrementiterator/)() override | Déplace l'itérateur d'un pas en arrière. |
| void [IncrementIterator](./incrementiterator/)() override | Déplace l'itérateur d'un pas en avant. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructeur. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructeur. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Constructeur de déplacement. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Déplace l'itérateur du nombre d'étapes spécifié. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destructeur. |

## Voir aussi

* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)