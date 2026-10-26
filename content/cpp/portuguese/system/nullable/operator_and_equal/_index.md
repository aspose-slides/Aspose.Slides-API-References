---
title: operator&=()
second_title: Referência da API Aspose.Slides para C++
description: Aplica operator&=() ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito.
type: docs
weight: 274
url: /pt/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) método

Aplica [operator&=()](./) ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T1 | O parâmetro de modelo para fazer o SFINAE funcionar. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | **bool** | Um valor booleano que é usado como valor do lado direito do [operator&=()](./) aplicado ao valor representado pelo objeto atual. |

### Valor de retorno

Uma referência ao próprio objeto.

## Veja também

* Classe [Nullable](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)