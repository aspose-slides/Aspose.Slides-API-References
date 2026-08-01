---
title: Fallback()
second_title: Aspose.Slides voor C++ API-referentie
description: Behandelt coderingsfout.
type: docs
weight: 27
url: /nl/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) methode


Behandelt coderingsfout.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charUnknown | char_t | Onbekend teken; wordt genegeerd. |
| index | int | Positie van onbekend teken; wordt genegeerd. |

### Retourwaarde

True als de vervangingsreeks is opgegeven en niet leeg is, anders false.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) methode


Behandelt coderingsfout.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charUnknownHigh | char_t | Hoge helft van het surrogate-paar dat de fout veroorzaakte. |
| charUnknownLow | char_t | Lage helft van het surrogate-paar dat de fout veroorzaakte. |
| index | int | Positie van onbekend teken; wordt genegeerd. |

### Retourwaarde

True als de vervangingsreeks is opgegeven en niet leeg is, anders false.

## Zie ook

* Klasse [EncoderReplacementFallbackBuffer](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)