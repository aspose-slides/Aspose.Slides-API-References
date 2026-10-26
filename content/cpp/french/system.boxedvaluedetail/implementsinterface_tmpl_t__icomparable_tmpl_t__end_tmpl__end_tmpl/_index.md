---
title: ImplementsInterface< T, IComparable< T > >
second_title: Référence de l'API Aspose.Slides pour C++
description: Prédicat de modèle qui vérifie si l'objet emballé doit implémenter l'interface IComparable par lui-même.
type: docs
weight: 53
url: /fr/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Prédicat de modèle qui vérifie si l'objet emballé doit implémenter [IComparable](../../system/icomparable/) interface par lui-même.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Voir aussi

* Espace de noms [System::BoxedValueDetail](../)
* Bibliothèque [Aspose.Slides](../../)