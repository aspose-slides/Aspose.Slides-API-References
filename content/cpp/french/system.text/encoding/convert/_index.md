---
title: Convert()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit des octets entre deux encodages.
type: docs
weight: 378
url: /fr/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) méthode


Convertit des octets entre deux encodages.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Encodage source. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Encodage de destination. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Octets à convertir. |

### Valeur de retour

Octets convertis.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) méthode


Convertit des octets entre deux encodages.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Encodage source. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Encodage de destination. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Octets à convertir. |
| index | int | Début de la tranche. |
| count | int | Taille de la tranche. |

### Valeur de retour

Octets convertis.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [Encoding](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)