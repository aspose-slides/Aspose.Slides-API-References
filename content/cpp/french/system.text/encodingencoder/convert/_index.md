---
title: Convert()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit des caractères en octets.
type: docs
weight: 1
url: /fr/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) méthode

Convertit des caractères en octets.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caractères à encoder. |
| charCount | int | Taille du tampon d'entrée. |
| bytes | **uint8_t** * | Tampon d'octets de destination. |
| byteCount | int | Taille du tableau de destination. |
| flush | **bool** | Si vrai, nettoie l'état interne de l'encodeur après le calcul. |
| charsUsed | int\& | Référence à la variable qui stocke le nombre de caractères lus. |
| bytesUsed | int\& | Référence à la variable qui stocke le nombre d'octets écrits. |
| completed | **bool**\& | Référence à la variable qui doit être définie sur vrai si le tampon d'entrée a été épuisé et sur faux sinon. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) méthode

Convertit des caractères en octets.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caractères à encoder. |
| charIndex | int | Décalage du tampon d'entrée. |
| charCount | int | Taille du tampon d'entrée. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tampon d'octets de destination. |
| byteIndex | int | Décalage du tableau de destination. |
| byteCount | int | Taille du tableau de destination. |
| flush | **bool** | Si vrai, nettoie l'état interne de l'encodeur après le calcul. |
| charsUsed | int\& | Référence à la variable qui stocke le nombre de caractères lus. |
| bytesUsed | int\& | Référence à la variable qui stocke le nombre d'octets écrits. |
| completed | **bool**\& | Référence à la variable qui doit être définie sur vrai si le tampon d'entrée a été épuisé et sur faux sinon. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [EncodingEncoder](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)