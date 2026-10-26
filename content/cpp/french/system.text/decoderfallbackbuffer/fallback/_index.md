---
title: Fallback()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémente la procédure de repli réelle.
type: docs
weight: 14
url: /fr/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) méthode


Implémente la procédure de repli réelle.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) d'octets incluant celui que le décodeur ne parvient pas à décoder. |
| index | int | Index de l'octet qui a déclenché l'erreur. |

### Valeur de retour

True if buffer processes unknown bytes, false if it ignores them.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [DecoderFallbackBuffer](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)