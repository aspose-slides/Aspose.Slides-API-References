---
title: IsStringLiteral
second_title: Referência da API Aspose.Slides para C++
description: Mágica de template para verificar se um tipo é um literal de string.
type: docs
weight: 1730
url: /pt/system/isstringliteral/
---
## struct IsStringLiteral

Mágica de template para verificar se um tipo é um literal de string.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Parâmetros do template

| Parâmetro | Descrição |
| --- | --- |
| T | tipo verificado. |
| CharT | tipo de caractere para comparar. |

## Veja Também

* namespace [System](../)
* biblioteca [Aspose.Slides](../../)