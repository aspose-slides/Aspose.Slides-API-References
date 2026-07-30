---
title: Fallback()
second_title: Aspose.Slides pro C++ API Reference
description: Zpracovává selhání kódování.
type: docs
weight: 27
url: /cs/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) metoda

Zpracovává selhání kódování.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| charUnknown | char_t | Neznámý znak; ignorováno. |
| index | int | Pozice neznámého znaku; ignorováno. |

### Návratová hodnota

True pokud je řetězec náhrady poskytnut a není prázdný, false jinak.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) metoda

Zpracovává selhání kódování.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| charUnknownHigh | char_t | Vyšší část páru surrogátů, který vyvolal chybu. |
| charUnknownLow | char_t | Nižší část páru surrogátů, který vyvolal chybu. |
| index | int | Pozice neznámého znaku; ignorováno. |

### Návratová hodnota

True pokud je řetězec náhrady poskytnut a není prázdný, false jinak.

## Viz také

* Třída [EncoderReplacementFallbackBuffer](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)