---
title: Fallback()
second_title: Aspose.Slides für C++ API-Referenz
description: Behandelt Kodierungsfehler.
type: docs
weight: 27
url: /de/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) Methode

Behandelt Kodierungsfehler.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| charUnknown | char_t | Unbekannte Zeichen; ignoriert. |
| index | int | Versatz unbekannter Zeichen; ignoriert. |

### Rückgabewert

Gibt nie tatsächlich zurück, wirft stattdessen eine Ausnahme.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) Methode

Behandelt Kodierungsfehler.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| charUnknownHigh | char_t | Höherer Teil des Surrogatpaares, das den Fehler ausgelöst hat. |
| charUnknownLow | char_t | Unterer Teil des Surrogatpaares, das den Fehler ausgelöst hat. |
| index | int | Versatz unbekannten Zeichens; ignoriert. |

### Rückgabewert

Gibt nie tatsächlich zurück, wirft stattdessen eine Ausnahme.

## Siehe auch

* Klasse [EncoderExceptionFallbackBuffer](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)