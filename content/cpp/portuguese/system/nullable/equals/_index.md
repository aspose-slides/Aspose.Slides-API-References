---
title: Equals()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o valor representado pelo objeto atual é igual ao valor representado pelo objeto Nullable especificado.
type: docs
weight: 131
url: /pt/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const método

Determina se o valor representado pelo objeto atual é igual ao valor representado pelo objeto [Nullable](../) especificado.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo subjacente do objeto [Nullable](../) a ser comparado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | Uma referência constante ao objeto [Nullable](../) a ser comparado |

### Valor de retorno

Verdadeiro se o valor representado pelo objeto atual for igual ao valor representado pelo objeto [Nullable](../) especificado, caso contrário - falso

## Veja também

* Classe [Nullable](../)
* Estrutura [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)