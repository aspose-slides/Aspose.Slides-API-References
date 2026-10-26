---
title: IsStringPointer
second_title: Aspose.Slides voor C++ API-referentie
description: Sjabloonmagie om te controleren of een type een pointer naar een tekenreeks is.
type: docs
weight: 1743
url: /nl/system/isstringpointer/
---
## IsStringPointer struct

Sjabloonmagie om te controleren of een type een pointer naar een tekenreeks is.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | gecontroleerd type. |
| CharT | Tekentype om tegen te controleren. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)