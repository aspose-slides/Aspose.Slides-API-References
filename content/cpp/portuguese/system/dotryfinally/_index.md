---
title: DoTryFinally()
second_title: Referência da API Aspose.Slides para C++
description: A única função que emula o comportamento da instrução try[-catch]-finally do C#. Durante a tradução da instrução try[-catch]-finally do C# com a opção do tradutor finally_statement_as_lambda definida como true, a instrução é traduzida para a invocação deste método.
type: docs
weight: 2445
url: /pt/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) função


A única função que emula o comportamento da instrução try[-catch]-finally do C#. Durante a tradução da instrução try[-catch]-finally do C# com a opção do tradutor finally_statement_as_lambda definida como true, a instrução é traduzida para a invocação deste método.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do objeto de função que implementa a parte try[-catch] da instrução try[-catch]-finally que está sendo emulada |
| F | O tipo do objeto de função que implementa a parte finally da instrução try[-catch]-finally que está sendo emulada |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tryBlock | T\&& | O objeto de função cujo corpo contém a implementação da parte try[-catch] da instrução try[-catch]-finally que está sendo emulada |
| finallyBlock | F\&& | O objeto de função cujo corpo contém a implementação da parte finally da instrução try[-catch]-finally que está sendo emulada |

## System::DoTryFinally(T\&&, F\&&) função


A única função que emula o comportamento da instrução try[-catch]-finally do C#. Durante a tradução da instrução try[-catch]-finally do C# com a opção do tradutor finally_statement_as_lambda definida como true, a instrução é traduzida para a invocação deste método. Esta sobrecarga trata o caso em que o valor de retorno do objeto de função que implementa a parte try[-catch] da instrução try[-catch]-finally é bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do objeto de função que implementa a parte try[-catch] da instrução try[-catch]-finally que está sendo emulada |
| F | O tipo do objeto de função que implementa a parte finally da instrução try[-catch]-finally que está sendo emulada |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tryBlock | T\&& | O objeto de função cujo corpo contém a implementação da parte try[-catch] da instrução try[-catch]-finally que está sendo emulada |
| finallyBlock | F\&& | O objeto de função cujo corpo contém a implementação da parte finally da instrução try[-catch]-finally que está sendo emulada |

## System::DoTryFinally(T\&&, F\&&) função


A única função que emula o comportamento da instrução try[-catch]-finally do C#. Durante a tradução da instrução try[-catch]-finally do C# com a opção do tradutor finally_statement_as_lambda definida como true, a instrução é traduzida para a invocação deste método. Esta sobrecarga trata o caso em que o valor de retorno do objeto de função que implementa a parte try[-catch] da instrução try[-catch]-finally é bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do objeto de função que implementa a parte try[-catch] da instrução try[-catch]-finally que está sendo emulada |
| F | O tipo do objeto de função que implementa a parte finally da instrução try[-catch]-finally que está sendo emulada |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tryBlock | T\&& | O objeto de função cujo corpo contém a implementação da parte try[-catch] da instrução try[-catch]-finally que está sendo emulada |
| finallyBlock | F\&& | O objeto de função cujo corpo contém a implementação da parte finally da instrução try[-catch]-finally que está sendo emulada |

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)