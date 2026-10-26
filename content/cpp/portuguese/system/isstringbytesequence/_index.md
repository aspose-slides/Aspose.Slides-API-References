---
title: IsStringByteSequence
second_title: Referência da API Aspose.Slides para C++
description: Mágica de template para verificar se um tipo é uma sequência de caracteres de string.
type: docs
weight: 1717
url: /pt/system/isstringbytesequence/
---
## IsStringByteSequence struct

Mágica de template para verificar se um tipo é uma sequência de caracteres de string.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Parâmetros de template

| Parâmetro | Descrição |
| --- | --- |
| T | tipo verificado. |
| CharT | Tipo de caractere a ser verificado. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)