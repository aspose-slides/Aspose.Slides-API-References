---
title: PrintToString()
second_title: Referência da API Aspose.Slides para C++
description: Imprime o objeto em string selecionando a função de serialização adequada.
type: docs
weight: 1
url: /pt/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) função

Imprime o objeto em string selecionando a função de serialização adequada.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) para imprimir. |

### Valor de retorno

[String](../../system/string/) representações do objeto passado.

## System::TestPredicates::Details::PrintToString(const T\&) função

Imprime contêineres no estilo ICollection em string imprimindo seus elementos (não mais que 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) para imprimir. |

### Valor de retorno

Representações de string combinadas dos elementos contidos.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) função

Imprime nullptr em string.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Valor de retorno

\"nullptr\" string.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) função

Imprime coleções [IEnumerable<bool>](../../system.collections.generic/ienumerable/) em string imprimindo seus elementos (não mais que 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) para imprimir. |

### Valor de retorno

Representações de string combinadas dos elementos contidos.

## Veja também

* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Estrutura [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Namespace [System::TestPredicates::Details](../)
* Biblioteca [Aspose.Slides](../../)