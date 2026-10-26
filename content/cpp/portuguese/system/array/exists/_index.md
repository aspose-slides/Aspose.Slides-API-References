---
title: Exists()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o objeto Array especificado contém um elemento que satisfaça os requisitos do predicado especificado.
type: docs
weight: 781
url: /pt/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) método

Determina se o objeto [Array](../) especificado contém um elemento que satisfaça os requisitos do predicado especificado.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | O array em que procurar o elemento |
| match | std::function\<**bool**(T)> | Objeto de função que define os requisitos e verifica se um elemento os satisfaz |

### Valor de Retorno

Verdadeiro se **arr** contém um elemento que satisfaz os requisitos definidos por **match**

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)