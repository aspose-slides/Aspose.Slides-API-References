---
title: Replace()
second_title: Referência da API Aspose.Slides para C++
description: Substitui substring através do builder.
type: docs
weight: 196
url: /pt/system.text/stringbuilder/replace/
---
## StringBuilder::Replace(const String\&, const String\&) method

Substitui substring através do builder.

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) a ser substituído. |
| newString | const [String](../../../system/string/)\& | String de substituição. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Replace(const String\&, const String\&, int, int) method

Substitui substring através do intervalo do builder.

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString, int position, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) a ser substituído. |
| newString | const [String](../../../system/string/)\& | String de substituição. |
| position | int | Posição inicial do intervalo de substituição do builder. |
| count | int | Comprimento do intervalo de substituição do builder. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Replace(char_t, char_t) method

Substitui caractere através do builder.

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldChar | char_t | Caractere a ser substituído. |
| newChar | char_t | Caractere de substituição. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::Replace(char_t, char_t, int, int) method

Substitui caractere através do intervalo do builder.

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar, int startIndex, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldChar | char_t | Caractere a ser substituído. |
| newChar | char_t | Caractere de substituição. |
| startIndex | int | Posição inicial do intervalo de substituição do builder. |
| count | int | Comprimento do intervalo de substituição do builder. |

### Valor de Retorno

Este ponteiro.

## Veja Também

* Classe [StringBuilder](../)
* Classe [String](../../../system/string/)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)