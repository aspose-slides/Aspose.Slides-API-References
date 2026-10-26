---
title: has_print_to_method
second_title: Aspose.Slides voor C++ API-referentie
description: "Controleert op een overload van de PrintTo-functie die het opgegeven type als eerste argument accepteert. Als er een overload bestaat, erft std::true_type, anders erft std::false_type."
type: docs
weight: 27
url: /nl/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct


Controleert op een overload van de PrintTo-functie die het opgegeven type als eerste argument accepteert. Als er een overload bestaat, erft std::true_type, anders erft std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type om te controleren. |
| Enable | Formeel argument zodat SFINAE werkt. |

## Zie ook

* Naamruimte [System::TestPredicates::TypeTraits](../)
* Bibliotheek [Aspose.Slides](../../)