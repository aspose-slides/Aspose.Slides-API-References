---
title: TrimEnd()
second_title: Referência da API Aspose.Slides para C++
description: Remove todos os caracteres de espaço em branco do final da string.
type: docs
weight: 703
url: /pt/system/string/trimend/
---
## String::TrimEnd() const method

Remove todos os caracteres de espaço em branco do final da string.

```cpp
String System::String::TrimEnd() const
```

### Valor de Retorno

[String](../) sem espaços em branco no início.

## String::TrimEnd(char_t) const method

Remove todas as ocorrências do caractere passado do final da string.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | Símbolo a remover. |

### Valor de Retorno

Resultado da remoção.

## String::TrimEnd(const String\&) const method

Remove todas as ocorrências dos caracteres passados do final da string.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) de caracteres a remover. |

### Valor de Retorno

[String](../) sem caracteres removidos.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const method

Remove todas as ocorrências dos caracteres passados do final da string.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a remover. |

### Valor de Retorno

[String](../) sem caracteres removidos.

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)