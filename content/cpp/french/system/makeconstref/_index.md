---
title: MakeConstRef
second_title: Référence API Aspose.Slides pour C++
description: Trait pour créer le type générique \"const reference\" s'il s'agit de String ou d'un type SmartPtr<>.
type: docs
weight: 1743
url: /fr/system/makeconstref/
---
## MakeConstRef struct

Trait pour créer le \"const reference\" de type générique s'il s'agit de [String](../string/) ou d'un type SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)