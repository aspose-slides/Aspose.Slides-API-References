---
title: IsBoxable
second_title: Aspose.Slides voor C++ API-referentie
description: Sjabloonpredicaat dat controleert of het verpakken van het opgegeven type wordt ondersteund.
type: docs
weight: 1665
url: /nl/system/isboxable/
---
## IsBoxable struct

Sjabloonpredicaat dat controleert of het verpakken van het opgegeven type wordt ondersteund.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type om te controleren |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)