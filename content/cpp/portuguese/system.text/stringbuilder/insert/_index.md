---
title: Insert()
second_title: Referência da API Aspose.Slides para C++
description: Insere string na posição fixa do construtor.
type: docs
weight: 183
url: /pt/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) método


Insere string na posição fixa do construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | Posição para inserir caracteres. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) para inserir. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Insert(int32_t, const String\&, int32_t) método


Insere string repetida na posição fixa do construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir caracteres. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) para inserir. |
| count | **int32_t** | Quantas vezes repetir a string **value**. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Insert(int, char_t) método


Insere caractere na posição fixa do construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | Posição para inserir caracteres. |
| ch | char_t | Caractere a ser inserido. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) método


Insere caracteres na posição fixa do construtor.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir caracteres. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) para inserir fatia de. |
| startIndex | int | [Array](../../../system/array/) índice inicial da fatia. |
| charCount | int | [Array](../../../system/array/) comprimento da fatia. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Insert(int, T) método


Insere valor na posição fixa do construtor.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| Parameter | tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | Posição para inserir caracteres. |
| value | T | Valor para formatar e inserir. |

### Valor de Retorno

Este ponteiro.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StringBuilder](../)
* Classe [String](../../../system/string/)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)