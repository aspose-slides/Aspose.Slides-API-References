---
title: IsList
second_title: Référence de l'API Aspose.Slides pour C++
description: "Vérifie si le type est une spécialisation System::Collections::Generic::List. Si c'est le cas, le membre value est défini sur true, sinon il est défini sur false."
type: docs
weight: 118
url: /fr/system.testpredicates.typetraits/islist/
---
## IsList typedef


Vérifie si le type est une spécialisation [System::Collections::Generic::List](../../system.collections.generic/list/). Si c'est le cas, le membre value est défini sur true, sinon il est défini sur false.

```cpp
using System::TestPredicates::TypeTraits::IsList = typedef std::is_same<T, System::Collections::Generic::List<typename T::ValueType> >
```


## Voir aussi

* Espace de noms [System::TestPredicates::TypeTraits](../)
* Bibliothèque [Aspose.Slides](../../)