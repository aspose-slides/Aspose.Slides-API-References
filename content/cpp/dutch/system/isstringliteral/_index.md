---
title: IsStringLiteral
second_title: Aspose.Slides voor C++ API-referentie
description: Sjabloonmagie om te controleren of een type een string literal is.
type: docs
weight: 1730
url: /nl/system/isstringliteral/
---
## IsStringLiteral struct


Sjabloonmagie om te controleren of een type een string literal is.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | type die wordt gecontroleerd. |
| CharT | Karaktertype om tegen te controleren. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)