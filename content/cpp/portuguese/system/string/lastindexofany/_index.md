---
title: LastIndexOfAny()
second_title: Referência da API Aspose.Slides para C++
description: Procura por quaisquer dos caracteres passados em toda a string de forma retroativa. Compara o último caractere da string com todos os caracteres em anyOf, depois compara o anterior e assim por diante. Retorna o índice da primeira correspondência encontrada.
type: docs
weight: 664
url: /pt/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const método

Procura por quaisquer dos caracteres passados em toda a string de forma retroativa. Compara o último caractere da string com todos os caracteres em anyOf, depois compara o anterior e assim por diante. Retorna o índice da primeira correspondência encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a serem procurados. A ordem não importa. |

### Valor de Retorno

[Index](../../index/) do último caractere correspondente ou -1 se não encontrado.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const método

Procura por quaisquer dos caracteres passados no substring de forma retroativa. Compara o último caractere da string com todos os caracteres em anyOf, depois compara o anterior e assim por diante. Retorna o índice da primeira correspondência encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a serem procurados. A ordem não importa. |
| startindex | **int32_t** | [Index](../../index/) para iniciar a busca a partir de. |

### Valor de Retorno

[Index](../../index/) do último caractere correspondente ou -1 se não encontrado.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const método

Procura por quaisquer dos caracteres passados no substring de forma retroativa. Compara o último caractere da string com todos os caracteres em anyOf, depois compara o anterior e assim por diante. Retorna o índice da primeira correspondência encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a serem procurados. A ordem não importa. |
| startindex | **int32_t** | [Index](../../index/) para iniciar a busca a partir de. |
| count | **int32_t** | Número de caracteres a serem percorridos. |

### Valor de Retorno

[Index](../../index/) do último caractere correspondente ou -1 se não encontrado.

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)