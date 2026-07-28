---
title: Fallback()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Implementuje rzeczywistą procedurę awaryjną.
type: docs
weight: 14
url: /pl/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) metoda


Implementuje rzeczywistą procedurę awaryjną.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| charUnknown | char_t | Enkoder znaków nie może zakodować. |
| index | int | [Index](../../../system/index/) znaku, który spowodował błąd. |

### Wartość zwracana

Prawda, jeśli bufor przetwarza nieznane znaki, fałsz, jeśli je ignoruje.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) metoda


Implementuje rzeczywistą procedurę awaryjną.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| charUnknownHigh | char_t | Wysoka część pary surrogatów, która spowodowała błąd. |
| charUnknownLow | char_t | Niska część pary surrogatów, która spowodowała błąd. |
| index | int | [Index](../../../system/index/) znaku, który spowodował błąd. |

### Wartość zwracana

Prawda, jeśli bufor przetwarza nieznane znaki, fałsz, jeśli je ignoruje.

## Zobacz także

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)