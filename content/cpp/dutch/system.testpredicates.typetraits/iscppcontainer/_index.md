---
title: IsCppContainer
second_title: Aspose.Slides voor C++ API-referentie
description: "Controleert of een specifiek type een STL-achtige container is. Daartoe controleert het op de leden types iterator en const_iterator. Als beide bestaan, erft het std::true_type, anders erft het std::false_type."
type: docs
weight: 40
url: /nl/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct


Controleert of een specifiek type een STL-achtige container is. Daartoe controleert het of de leden types iterator en const_iterator bestaan. Als beide bestaan, erft het std::true_type, anders erft het std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```


### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Te controleren type. |
| Enable | Formeel argument om SFINAE te laten werken. |

## Zie ook

* Namespace [System::TestPredicates::TypeTraits](../)
* Bibliotheek [Aspose.Slides](../../)