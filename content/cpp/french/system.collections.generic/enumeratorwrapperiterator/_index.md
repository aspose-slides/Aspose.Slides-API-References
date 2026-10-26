---
title: EnumeratorWrapperIterator
second_title: Référence de l'API Aspose.Slides pour C++
description: Itérateur qui encapsule l'énumérateur pré-créé et redirige tous les appels vers celui-ci.
type: docs
weight: 196
url: /fr/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator classe


Itérateur qui encapsule l'énumérateur pré-créé et redirige tous les appels vers celui-ci.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Element | Type d'élément. |
## Méthodes

| Méthode | Description |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Clone l'itérateur actuel. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Avance l'itérateur d'un pas. Doit mettre à jour m_is_end et m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Vérifie si deux itérateurs pointent vers le même élément. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destructeur. |

## Voir aussi

* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)