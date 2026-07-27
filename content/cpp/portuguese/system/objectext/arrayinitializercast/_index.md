---
title: ArrayInitializerCast()
second_title: Referência da API Aspose.Slides para C++
description: Converte valores fundamentais de array (que C# faz implicitamente, mas C++ aparentemente não).
type: docs
weight: 209
url: /pt/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) método

Converte valores fundamentais de array (que C# faz implicitamente, mas C++ aparentemente não).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| To | Tipo de destino. |
| From | Tipos de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | From ... | Valores a converter e inserir no array de destino. |

### Valor de Retorno

[Array](../../array/) contendo cópias convertidas de todos os argumentos na mesma ordem.

## Veja Também

* Classe [ObjectExt](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)