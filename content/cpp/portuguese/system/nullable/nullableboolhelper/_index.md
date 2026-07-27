---
title: NullableBoolHelper()
second_title: Referência da API Aspose.Slides para C++
description: Função auxiliar para verificar se this e other são ambos não nulos e chamar uma lambda nesse caso. Usada em implementações.
type: docs
weight: 105
url: /pt/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

Função auxiliar para verificar se **this** e **other** são ambos não nulos e chamar uma lambda nesse caso. Usada em implementações.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Outro tipo anulável. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | Outro valor anulável para comparar. |
| f | const std::function\<**bool**()>\& | Lambda a ser chamada se **this** e **other** não forem nulos. |
| default_if_both_are_null | **bool** | Valor de retorno se ambos os valores forem nulos. |

### Valor de Retorno

false se **this** ou **other** for nulo; **default_if_both_are_null** se ambos forem nulos; resultado da chamada de **f** se ambos não forem nulos.

## Veja Também

* Classe [Nullable](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)