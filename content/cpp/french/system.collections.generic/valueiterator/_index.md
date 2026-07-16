---
title: ValueIterator
second_title: Référence de l'API Aspose.Slides pour C++
description: Itérateur de dictionnaire qui fournit un accès aux valeurs.
type: docs
weight: 625
url: /fr/system.collections.generic/valueiterator/
---
## ValueIterator classe

[Dictionary](../dictionary/) itérateur qui fournit un accès aux valeurs.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |
## Méthodes

| Method | Description |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Clone l'itérateur actuel. |
| void [DecrementIterator](./decrementiterator/)() override | Déplace l'itérateur d'un pas en arrière. |
| void [IncrementIterator](./incrementiterator/)() override | Déplace l'itérateur d'un pas en avant. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Déplace l'itérateur du nombre de pas spécifié. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructeur. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructeur. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Constructeur de déplacement. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destructeur. |

## Voir aussi

* espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)