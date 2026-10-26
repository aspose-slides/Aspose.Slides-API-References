---
title: Fallback()
second_title: Référence de l'API Aspose.Slides pour C++
description: Gère l'échec du codage.
type: docs
weight: 27
url: /fr/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) méthode

Gère l'échec du codage.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Caractères inconnus ; ignorés. |
| index | int | Décalage des caractères inconnus ; ignoré. |

### Valeur de retour

Ne renvoie jamais réellement, génère une exception à la place.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) méthode

Gère l'échec du codage.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | Partie haute de la paire de substitution qui a déclenché l'erreur. |
| charUnknownLow | char_t | Partie basse de la paire de substitution qui a déclenché l'erreur. |
| index | int | Décalage du caractère inconnu ; ignoré. |

### Valeur de retour

Ne renvoie jamais réellement, génère une exception à la place.

## Voir aussi

* Classe [EncoderExceptionFallbackBuffer](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)