---
title: TrimStart()
second_title: Referência da API Aspose.Slides para C++
description: Remove todos os caracteres de espaço em branco do início da string.
type: docs
weight: 690
url: /pt/system/string/trimstart/
---
## String::TrimStart() const método

Remove todos os caracteres de espaço em branco do início da string.

```cpp
String System::String::TrimStart() const
```


### Valor de Retorno

[String](../) sem espaços em branco no início.

## String::TrimStart(char_t) const método

Remove todas as ocorrências do caractere passado do início da string.

```cpp
String System::String::TrimStart(char_t ch) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ch | char_t | Símbolo a ser removido. |

### Valor de Retorno

Resultado da remoção.

## String::TrimStart(const String\&) const método

Remove todas as ocorrências dos caracteres passados do início da string.

```cpp
String System::String::TrimStart(const String &anyOf) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) de caracteres a remover. |

### Valor de Retorno

[String](../) sem os caracteres removidos.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const método

Remove todas as ocorrências dos caracteres passados do início da string.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a remover. |

### Valor de Retorno

[String](../) sem os caracteres removidos.

## Ver Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)