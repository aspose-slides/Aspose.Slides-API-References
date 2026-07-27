---
title: IsBoxable
second_title: Referência da API Aspose.Slides para C++
description: Predicado de modelo que verifica se o empacotamento do tipo especificado é suportado.
type: docs
weight: 1665
url: /pt/system/isboxable/
---
## IsBoxable struct


Predicado de modelo que verifica se o empacotamento do tipo especificado é suportado.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo a ser verificado |

## Ver também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)