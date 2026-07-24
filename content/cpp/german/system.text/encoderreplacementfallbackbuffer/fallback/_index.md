---
title: Fallback()
second_title: Aspose.Slides für C++ API Referenz
description: Behandelt Kodierungsfehler.
type: docs
weight: 27
url: /de/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) Methode


Behandelt Kodierungsfehler.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| charUnknown | char_t | Unbekanntes Zeichen; ignoriert. |
| index | int | Unbekannte Zeichenposition; ignoriert. |

### Rückgabewert

True, wenn ein Ersatzstring bereitgestellt wird und nicht leer ist, sonst false.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) Methode


Behandelt Kodierungsfehler.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| charUnknownHigh | char_t | Hoher Teil des Surrogatpaars, das den Fehler ausgelöst hat. |
| charUnknownLow | char_t | Niedriger Teil des Surrogatpaars, das den Fehler ausgelöst hat. |
| index | int | Unbekannte Zeichenposition; ignoriert. |

### Rückgabewert

True, wenn ein Ersatzstring bereitgestellt wird und nicht leer ist, sonst false.

## Siehe auch

* Klasse [EncoderReplacementFallbackBuffer](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)