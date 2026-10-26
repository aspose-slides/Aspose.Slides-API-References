---
title: Fallback()
second_title: Référence de l'API Aspose.Slides pour C++
description: Gère les échecs d'encodage.
type: docs
weight: 27
url: /fr/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) méthode

Gère les échecs d'encodage.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Caractère inconnu ; ignoré. |
| index | int | Position du caractère inconnu ; ignoré. |

### Valeur de retour

True si la chaîne de remplacement est fournie et n'est pas vide, false sinon.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) méthode

Gère les échecs d'encodage.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | Partie haute de la paire de substitution qui a déclenché l'erreur. |
| charUnknownLow | char_t | Partie basse de la paire de substitution qui a déclenché l'erreur. |
| index | int | Position du caractère inconnu ; ignoré. |

### Valeur de retour

True si la chaîne de remplacement est fournie et n'est pas vide, false sinon.

## Voir aussi

* Classe [EncoderReplacementFallbackBuffer](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)