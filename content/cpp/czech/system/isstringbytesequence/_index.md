---
title: IsStringByteSequence
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Magie šablon pro kontrolu, zda je typ sekvencí znaků řetězce.
type: docs
weight: 1717
url: /cs/system/isstringbytesequence/
---
## IsStringByteSequence struct

Magie šablon pro kontrolu, zda je typ sekvencí znaků řetězce.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | kontrolovaný typ. |
| CharT | Typ znaku, proti kterému se kontroluje. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)