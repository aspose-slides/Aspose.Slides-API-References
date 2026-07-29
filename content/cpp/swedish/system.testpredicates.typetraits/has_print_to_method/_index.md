---
title: has_print_to_method
second_title: Aspose.Slides för C++ API-referens
description: "Kontrollerar om det finns en överlagring av PrintTo-funktionen som accepterar den angivna typen som första argument. Om en överlagring finns, ärver std::true_type, annars ärver std::false_type."
type: docs
weight: 27
url: /sv/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct


Kontrollerar om det finns en överlagring av PrintTo-funktionen som accepterar den angivna typen som första argument. Om en överlagring finns, ärver std::true_type, annars ärver std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att kontrollera. |
| Enable | Formellt argument för att SFINAE ska fungera. |

## Se även

* Namnrymd [System::TestPredicates::TypeTraits](../)
* Bibliotek [Aspose.Slides](../../)