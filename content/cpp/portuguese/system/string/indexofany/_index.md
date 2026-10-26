---
title: IndexOfAny()
second_title: Referência da API Aspose.Slides para C++
description: Busca avançada de caractere.
type: docs
weight: 638
url: /pt/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const método


Character forward lookup.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c | char_t | Caractere a ser procurado. |
| startIndex | int | [Index](../../index/) para iniciar a pesquisa em. |

### Valor de Retorno

[Index](../../index/) da posição do primeiro caractere a partir de startIndex ou -1 se não encontrado.

## String::IndexOfAny(const String\&, int) const método


Consequently looks for all characters of str in this. If first character is found, its position is returned, otherwise looks for the second one and so on.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) de caracteres a serem procurados. A ordem dos caracteres importa. |
| startIndex | int | Position to start lookup from. |

### Valor de Retorno

[Index](../../index/) do primeiro caractere encontrado ou -1 se nenhum for encontrado.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const método


Looks for any of passed characters through the whole string. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a serem procurados. A ordem não importa. |

### Valor de Retorno

[Index](../../index/) do primeiro caractere correspondente ou -1 se não encontrado.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const método


Looks for any of passed characters through substring. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a serem procurados. A ordem não importa. |
| startindex | **int32_t** | [Index](../../index/) para iniciar a pesquisa a partir de. |

### Valor de Retorno

[Index](../../index/) do primeiro caractere correspondente ou -1 se não encontrado.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const método


Looks for any of passed characters through substring. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a serem procurados. A ordem não importa. |
| startindex | **int32_t** | [Index](../../index/) para iniciar a pesquisa a partir de. |
| count | **int32_t** | Número de caracteres a serem examinados. |

### Valor de Retorno

[Index](../../index/) do primeiro caractere correspondente ou -1 se não encontrado.

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)