---
title: DictionaryIterator
second_title: Référence de l'API Aspose.Slides pour C++
description: Itérateur de dictionnaire qui fournit la notation KeyValuePair.
type: docs
weight: 157
url: /fr/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator classe

[Dictionary](../dictionary/) itérateur qui fournit la notation [KeyValuePair](../keyvaluepair/).

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |

## Méthodes

| Méthode | Description |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Clone l'itérateur actuel. |
| void [DecrementIterator](./decrementiterator/)() override | Déplace l'itérateur d'un pas en arrière. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructeur. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructeur. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Constructeur de déplacement. |
| void [IncrementIterator](./incrementiterator/)() override | Déplace l'itérateur d'un pas en avant. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Déplace l'itérateur du nombre spécifié de pas. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destructeur. |

## Voir aussi

* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)