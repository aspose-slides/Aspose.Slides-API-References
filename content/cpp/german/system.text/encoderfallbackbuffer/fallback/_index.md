---
title: Fallback()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementiert das eigentliche Fallback-Verfahren.
type: docs
weight: 14
url: /de/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) Methode


Implementiert das eigentliche Fallback-Verfahren.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| charUnknown | char_t | Der Zeichenencoder kann das Zeichen nicht codieren. |
| index | int | [Index](../../../system/index/) des Zeichens, das den Fehler auslöste. |

### Rückgabewert

True, wenn der Puffer unbekannte Zeichen verarbeitet, false, wenn er sie ignoriert.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) Methode


Implementiert das eigentliche Fallback-Verfahren.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| charUnknownHigh | char_t | Hoher Teil des Surrogatpaares, das den Fehler auslöste. |
| charUnknownLow | char_t | Niedriger Teil des Surrogatpaares, das den Fehler auslöste. |
| index | int | [Index](../../../system/index/) des Zeichens, das den Fehler auslöste. |

### Rückgabewert

True, wenn der Puffer unbekannte Zeichen verarbeitet, false, wenn er sie ignoriert.

## Siehe auch

* Klasse [EncoderFallbackBuffer](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)