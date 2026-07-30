---
title: IsStringPointer
second_title: Reference API Aspose.Slides pro C++
description: Šablonová magie pro kontrolu, zda je typ ukazatelem na řetězec znaků.
type: docs
weight: 1743
url: /cs/system/isstringpointer/
---
## IsStringPointer struct

Šablonová magie pro kontrolu, zda je typ ukazatelem na řetězec znaků.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | kontrolovaný typ. |
| CharT | Typ znaku, proti kterému se kontroluje. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)