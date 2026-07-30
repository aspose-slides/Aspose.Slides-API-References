---
title: IsStringLiteral
second_title: Aspose.Slides pro C++ referenci API
description: Kouzlo šablony pro kontrolu, zda je typ řetězcovým literálem.
type: docs
weight: 1730
url: /cs/system/isstringliteral/
---
## IsStringLiteral struct

Kouzlo šablony pro kontrolu, zda je typ řetězcový literál.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | typ, který je kontrolován. |
| CharT | typ znaku, proti kterému se kontroluje. |

## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)