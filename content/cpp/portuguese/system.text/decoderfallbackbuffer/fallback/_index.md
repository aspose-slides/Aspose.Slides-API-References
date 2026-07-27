---
title: Fallback()
second_title: Referência da API Aspose.Slides para C++
description: Implementa o procedimento real de fallback.
type: docs
weight: 14
url: /pt/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) método

Implementa o procedimento real de fallback.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) de bytes incluindo o que o decodificador falha ao decodificar. |
| index | int | [Index](../../../system/index/) do byte que desencadeou o erro. |

### Valor de retorno

True se o buffer processar bytes desconhecidos, false se os ignorar.

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)