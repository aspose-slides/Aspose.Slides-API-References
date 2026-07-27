---
title: GetByteCount()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o número de bytes necessários para codificar um buffer.
type: docs
weight: 40
url: /pt/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) método

Obtém o número de bytes necessários para codificar um buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| index | int | [Buffer](../../../system/buffer/) deslocamento. |
| count | int | Número de caracteres a codificar. |
| flush | **bool** | Se true, limpa o estado interno do codificador após o cálculo. |

### Valor de Retorno

Número de bytes necessários para codificar o buffer.

## Encoder::GetByteCount(const char_t *, int, bool) método

Obtém o número de bytes necessários para codificar um buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| count | int | Número de caracteres a codificar. |
| flush | **bool** | Se true, limpa o estado interno do codificador após o cálculo. |

### Valor de Retorno

Número de bytes necessários para codificar o buffer.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Encoder](../)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)