---
title: GetDescription()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nome da constante de enumeração que possui o valor especificado.
type: docs
weight: 53
url: /pt/system/enum/getdescription/
---
## Enum::GetDescription(T) método

Retorna o nome da constante de enumeração que possui o valor especificado.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T | O valor da constante de enumeração cujo nome deve ser retornado |

### Valor de Retorno

O nome da constante de enumeração especificada

## Veja Também

* Typedef [UnderlyingType](../underlyingtype/)
* Classe [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)