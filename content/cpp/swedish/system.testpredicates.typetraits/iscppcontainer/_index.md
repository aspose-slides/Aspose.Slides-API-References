---
title: IsCppContainer
second_title: Aspose.Slides för C++ API-referens
description: "Kontrollerar om en specifik typ är en STL-style container. För att göra detta kontrolleras om medlemstyperna iterator och const_iterator finns. Om båda finns ärver den std::true_type, annars ärver den std::false_type."
type: docs
weight: 40
url: /sv/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Kontrollerar om en specifik typ är en STL-style container. För att göra det kontrolleras om medlemstyperna iterator och const_iterator finns. Om båda finns ärver den std::true_type, annars ärver den std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att kontrollera. |
| Enable | Formellt argument för att SFINAE ska fungera. |

## Se också

* Namnrymd [System::TestPredicates::TypeTraits](../)
* Bibliotek [Aspose.Slides](../../)