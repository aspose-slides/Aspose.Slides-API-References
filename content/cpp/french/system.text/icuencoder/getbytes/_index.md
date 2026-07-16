---
title: GetBytes()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les octets résultant du codage d'un tampon.
type: docs
weight: 53
url: /fr/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Obtient les octets résultant du codage d'un tampon.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caractères à encoder. |
| charIndex | int | Décalage du tableau source. |
| charCount | int | Longueur de la sous-section du tableau source. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tampon d'octets de destination. |
| byteIndex | int | Décalage du tampon de destination. |
| flush | **bool** | Si vrai, nettoie l'état interne de l'encodeur après le calcul. |

### Valeur de retour

Nombre d'octets écrits.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Obtient les octets résultant du codage d'un tampon.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caractères à encoder. |
| charCount | int | Longueur du tableau source. |
| bytes | **uint8_t** * | Tampon d'octets de destination. |
| byteCount | int | Taille du tampon de destination. |
| flush | **bool** | Si vrai, nettoie l'état interne de l'encodeur après le calcul. |

### Valeur de retour

Nombre d'octets écrits.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)