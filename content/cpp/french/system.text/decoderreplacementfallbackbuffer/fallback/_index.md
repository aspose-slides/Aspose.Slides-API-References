---
title: Fallback()
second_title: Référence API Aspose.Slides pour C++
description: Gère l'échec du décodage.
type: docs
weight: 27
url: /fr/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) method

Gère l'échec du décodage.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) d'octets inconnus; ignoré. |
| index | int | Décalage des octets inconnus; ignoré. |

### Return Value

Vrai si une chaîne de remplacement est fournie et n’est pas vide, faux sinon.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)