---
title: IsStringByteSequence
second_title: Aspose.Slides voor C++ API-referentie
description: Sjabloonmagie om te controleren of een type een reeks tekenreeks-karakters is.
type: docs
weight: 1717
url: /nl/system/isstringbytesequence/
---
## IsStringByteSequence struct

Sjabloonmagie om te controleren of een type een reeks tekenreeks-karakters is.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | gecontroleerd type. |
| CharT | Teken-type om tegen te controleren. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)