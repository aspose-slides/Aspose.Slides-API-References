---
title: Trim()
second_title: Aspose.Slides para C++ - Referência da API
description: Remove todos os caracteres de espaço em branco tanto do início quanto do fim da string.
type: docs
weight: 677
url: /pt/system/string/trim/
---
## String::Trim() const método

Remove todos os caracteres de espaço em branco tanto do início quanto do fim da string.

```cpp
String System::String::Trim() const
```

### Valor de Retorno

[String](../) sem espaços em branco no início ou no fim.

## String::Trim(char_t) const método

Remove todas as ocorrências do caractere passado tanto do início quanto do fim da string.

```cpp
String System::String::Trim(char_t ch) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ch | char_t | Símbolo a remover. |

### Valor de Retorno

Resultado da remoção.

## String::Trim(const String\&) const método

Remove todas as ocorrências dos caracteres passados tanto do início quanto do fim da string.

```cpp
String System::String::Trim(const String &anyOf) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) de caracteres a remover. |

### Valor de Retorno

[String](../) sem caracteres removidos.

## String::Trim(const ArrayPtr\<char_t\>\&) const método

Remove todas as ocorrências dos caracteres passados tanto do início quanto do fim da string.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a remover. |

### Valor de Retorno

[String](../) sem caracteres removidos.

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)