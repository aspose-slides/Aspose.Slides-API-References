---
title: Fallback()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémente la procédure de repli réelle.
type: docs
weight: 14
url: /fr/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) méthode

Implémente la procédure de repli réelle.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | L'encodeur de caractères échoue à encoder. |
| index | int | Indice du caractère qui a déclenché l'erreur. |

### Valeur de retour

True si le tampon traite les caractères inconnus, false s'il les ignore.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) méthode

Implémente la procédure de repli réelle.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | Partie haute de la paire substitut qui a déclenché l'erreur. |
| charUnknownLow | char_t | Partie basse de la paire substitut qui a déclenché l'erreur. |
| index | int | Indice du caractère qui a déclenché l'erreur. |

### Valeur de retour

True si le tampon traite les caractères inconnus, false s'il les ignore.

## Voir aussi

* Classe [EncoderFallbackBuffer](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)