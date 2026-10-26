---
title: Append()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona caractere ao construtor.
type: docs
weight: 118
url: /pt/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) método


Adiciona caractere ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c | char_t | Valor do caractere. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(char_t, int) método


Adiciona caracteres ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c | char_t | Valor do caractere. |
| count | int | Quantas vezes repetir o caractere inserido. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) método


Adiciona array de caracteres ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Caracteres a adicionar. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) método


Adiciona fatia de array de caracteres ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Caracteres a adicionar. |
| startIndex | int | Índice inicial da fatia. |
| charCount | int | Comprimento da fatia. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(const String\&) método


Adiciona cadeia de caracteres ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) a ser adicionado. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(const String\&, int, int) método


Adiciona fatia de cadeia de caracteres ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) a ser adicionado. |
| startIndex | int | Índice inicial da fatia. |
| charCount | int | Comprimento da fatia. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(const SharedPtr\<T\>\&) método


Adiciona a representação em cadeia de caracteres do objeto ao construtor.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../../system/object/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) para serializar e adicionar. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) método


Adiciona o conteúdo do construtor ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Construtor do qual adicionar o conteúdo. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(float) método


Adiciona valor de ponto flutuante ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| f | **float** | Valor para serializar e adicionar. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(double) método


Adiciona valor de ponto flutuante ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| df | **double** | Valor para serializar e adicionar. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(int) método


Adiciona valor inteiro ao construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | int | Valor para serializar e adicionar. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(T) método


Adiciona valor aritmético ao construtor.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo aritmético. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T | Valor para serializar e adicionar. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Append(E) método


Adiciona representação em string do valor enum ao construtor.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| E | [Enum](../../../system/enum/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| e | E | Valor para serializar e adicionar. |

### Valor de Retorno

Este ponteiro.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)