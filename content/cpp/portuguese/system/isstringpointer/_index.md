---
title: IsStringPointer
second_title: Aspose.Slides para C++ - Referência da API
description: Mágica de template para verificar se um tipo é um ponteiro para string de caracteres.
type: docs
weight: 1743
url: /pt/system/isstringpointer/
---
## IsStringPointer struct


Mágica de template para verificar se um tipo é um ponteiro para string de caracteres.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo verificado. |
| CharT | Tipo de caractere a ser comparado. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)