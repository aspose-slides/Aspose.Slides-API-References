---
title: has_data_method
second_title: Aspose.Slides för C++ API-referens
description: "Kontrollerar om en typ har data()-metod. Om den har det ärver den std::true_type, annars ärver den std::false_type."
type: docs
weight: 1
url: /sv/system.testpredicates.typetraits/has_data_method/
---
## has_data_method struct

Kontrollerar om en typ har data()-metod. Om den har det, ärver std::true_type, annars ärver std::false_type.

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att kontrollera. |
| Enable | Formellt argument för att SFINAE ska fungera. |

## Se också

* Namnrymd [System::TestPredicates::TypeTraits](../)
* Bibliotek [Aspose.Slides](../../)