---
title: PrintToStringImpl()
second_title: Referência da API Aspose.Slides para C++
description: "Imprime a subclasse System::Object para string usando o método ToString()."
type: docs
weight: 14
url: /pt/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) função


Imprime a subclasse [System::Object](../../system/object/) para string usando o método ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de classe final. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Ponteiro para o objeto a ser impresso. |
| s | long long | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

[String](../../system/string/) representação do objeto passado ou "nullptr", se **value** for nulo.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) função


Imprime a subclasse [System::Object](../../system/object/) para string usando o método ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de classe final. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Ponteiro para o objeto a ser impresso. |
| s | long long | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

[String](../../system/string/) representação do objeto passado ou "nullptr", se **value** for nulo.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) função


Imprime o objeto para string usando o método ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) para imprimir. |
| s | long long | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

[String](../../system/string/) representação do objeto passado.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) função


Imprime o objeto para string usando o método PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) para imprimir. |
| s | long long | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

[String](../../system/string/) representação do objeto passado.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) função


Imprime o objeto para string usando o método PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) para imprimir. |
| s | long long | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

[String](../../system/string/) representação do objeto passado.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) função


Imprime o par para string.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Primeiro argumento de tipo do par. |
| T2 | Segundo argumento de tipo do par. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) para imprimir. |
| s | long long | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

Representações de string conjuntas dos componentes primeiro e segundo do par.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) função


Imprime o par para string.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Primeiro argumento de tipo do par. |
| T2 | Segundo argumento de tipo do par. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) para imprimir. |
| s | long long | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

Representações de string conjuntas dos componentes primeiro e segundo do par.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) função


Imprime contêineres estilo STL para string imprimindo seus elementos (não mais que 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) para imprimir. |
| s | long long | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

Representações de string conjuntas dos elementos contidos.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) função


Imprime outros tipos para string usando funções fornecidas pelo gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) para imprimir. |
| s | int | Um parâmetro de serviço que funciona como seletor de sobrecarga de função com base no tipo deste parâmetro; o valor do parâmetro é ignorado |

### Valor de Retorno

[String](../../system/string/) representações do objeto passado.

## Veja Também

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [WeakPtr](../../system/weakptr/)
* Classe [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Classe [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)