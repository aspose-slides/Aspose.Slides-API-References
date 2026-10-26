---
title: Fallback()
second_title: Aspose.Slides voor C++ API-referentie
description: Behandelt coderingsfout.
type: docs
weight: 27
url: /nl/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) methode

Behandelt coderingsfout.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charUnknown | char_t | Onbekende tekens; genegeerd. |
| index | int | Offset van onbekende tekens; genegeerd. |

### Retourwaarde

Retourneert nooit echt, gooit in plaats daarvan een uitzondering.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) methode

Behandelt coderingsfout.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charUnknownHigh | char_t | Hoge deel van het surrogate-paar dat de fout veroorzaakte. |
| charUnknownLow | char_t | Lage deel van het surrogate-paar dat de fout veroorzaakte. |
| index | int | Offset van onbekend teken; genegeerd. |

### Retourwaarde

Retourneert nooit echt, gooit in plaats daarvan een uitzondering.

## Zie ook

* Klasse [EncoderExceptionFallbackBuffer](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)