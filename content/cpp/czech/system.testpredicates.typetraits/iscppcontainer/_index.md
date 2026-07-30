---
title: IsCppContainer
second_title: Aspose.Slides pro C++ API Reference
description: "Kontroluje, zda je konkrétní typ kontejnerem ve stylu STL. K tomu kontroluje existenci členských typů iterator a const_iterator. Pokud oba existují, dědí std::true_type, jinak dědí std::false_type."
type: docs
weight: 40
url: /cs/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Kontroluje, zda je konkrétní typ kontejnerem ve stylu STL. K tomu kontroluje existence členských typů iterator a const_iterator. Pokud oba existují, dědí std::true_type, jinak dědí std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, který se kontroluje. |
| Enable | Formální argument pro fungování SFINAE. |

## Viz také

* Jmenný prostor [System::TestPredicates::TypeTraits](../)
* Knihovna [Aspose.Slides](../../)