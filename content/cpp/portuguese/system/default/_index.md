---
title: Default()
second_title: Aspose.Slides for C++ Referência da API
description: Retorna a referência para a única instância construída por padrão do tipo de exceção.
type: docs
weight: 2224
url: /pt/system/default/
---
## System::Default() função

Retorna a referência para a única instância construída por padrão do tipo de exceção.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo cuja instância é retornada |

## System::Default() função

Retorna a referência para a única instância construída por padrão do tipo que não é exceção.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo cuja instância é retornada |

## Veja também

* Estrutura [IsExceptionWrapper](../isexceptionwrapper/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)