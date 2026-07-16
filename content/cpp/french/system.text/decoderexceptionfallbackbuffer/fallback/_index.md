---
title: Fallback()
second_title: Référence de l'API Aspose.Slides for C++
description: Gère l'échec du décodage.
type: docs
weight: 27
url: /fr/system.text/decoderexceptionfallbackbuffer/fallback/
---
## DecoderExceptionFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) method

Gère l'échec du décodage.

```cpp
virtual bool System::Text::DecoderExceptionFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) d'octets inconnus ; ignoré. |
| index | int | Décalage des octets inconnus ; ignoré. |

### Valeur de retour

Ne renvoie jamais réellement, lance une exception à la place.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [DecoderExceptionFallbackBuffer](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)