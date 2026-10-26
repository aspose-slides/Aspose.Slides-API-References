---
title: ToString()
second_title: Referência da API Aspose.Slides para C++
description: Substituição do método ToString do C# para funcionar em qualquer tipo C++.
type: docs
weight: 27
url: /pt/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Nullable](../../nullable/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) objeto para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(const T\&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Enum](../../enum/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) valor para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(const T\&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de ponteiro inteligente. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) valor para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(T\&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de ponteiro inteligente ou [ExceptionWrapper](../../exceptionwrapper/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T\& | Ponteiro inteligente ou [ExceptionWrapper](../../exceptionwrapper/) para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(T\&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo escalar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T\& | Valor escalar para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(T\&&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo escalar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T\&& | Valor escalar para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(T\&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de estrutura. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T\& | Valor de estrutura para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(const T\&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de estrutura. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | Valor de estrutura para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## ObjectExt::ToString(T\&&) método


Substituição do método ToString do C# para funcionar em qualquer tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo escalar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T\&& | Valor escalar para converter em string. |

### Valor de Retorno

[String](../../string/) representação de **obj**.

## Veja também

* Classe [String](../../string/)
* Classe [ObjectExt](../)
* Classe [Nullable](../../nullable/)
* Estrutura [IsSmartPtr](../../issmartptr/)
* Estrutura [IsExceptionWrapper](../../isexceptionwrapper/)
* Estrutura [IsNullable](../../isnullable/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)