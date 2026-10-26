---
title: operator|=()
second_title: Aspose.Slides para C++ Referência da API
description: Aplica operator|=() ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito.
type: docs
weight: 261
url: /pt/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) método

Aplica [operator|=()](./) ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O parâmetro de modelo para fazer SFINAE funcionar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | **bool** | Um valor booleano que é usado como valor do lado direito do [operator|=()](./) aplicado ao valor representado pelo objeto atual. |

### Valor de retorno

Uma referência ao próprio objeto.

## Veja também

* Classe [Nullable](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)