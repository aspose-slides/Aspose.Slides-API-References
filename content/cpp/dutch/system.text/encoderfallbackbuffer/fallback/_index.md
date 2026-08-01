---
title: Fallback()
second_title: Aspose.Slides for C++ API-referentie
description: Implementeert de daadwerkelijke fallback-procedure.
type: docs
weight: 14
url: /nl/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) methode

Implementeert de daadwerkelijke fallback-procedure.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charUnknown | char_t | De tekenencoder kan het teken niet coderen. |
| index | int | [Index](../../../system/index/) van het teken dat de fout veroorzaakte. |

### Retourwaarde

Waar als de buffer onbekende tekens verwerkt, onwaar als het ze negeert.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) methode

Implementeert de daadwerkelijke fallback-procedure.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charUnknownHigh | char_t | Hoog deel van het surrogate-paar dat de fout veroorzaakte. |
| charUnknownLow | char_t | Laag deel van het surrogate-paar dat de fout veroorzaakte. |
| index | int | [Index](../../../system/index/) van het teken dat de fout veroorzaakte. |

### Retourwaarde

Waar als de buffer onbekende tekens verwerkt, onwaar als het ze negeert.

## Zie ook

* Klasse [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)