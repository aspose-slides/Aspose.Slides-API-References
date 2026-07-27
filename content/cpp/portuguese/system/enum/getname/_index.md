---
title: GetName()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nome da constante de enumeração que tem o valor especificado.
type: docs
weight: 40
url: /pt/system/enum/getname/
---
## Enum::GetName(T) método

Retorna o nome da constante de enumeração que tem o valor especificado.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T | O valor da constante de enum cujo nome será retornado |

### Valor de retorno

O nome da constante enum especificada

## Veja também

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)