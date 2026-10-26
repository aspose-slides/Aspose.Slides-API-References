---
title: GetBytes()
second_title: Aspose.Slides pro C++ – dokumentace API
description: Získá bajty, které jsou výsledkem kódování bufferu.
type: docs
weight: 53
url: /cs/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metoda


Získá bajty, které jsou výsledkem kódování bufferu.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |
| charIndex | int | Posun zdrojového pole. |
| charCount | int | Délka podpole zdrojového pole. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Cílový buffer bajtů. |
| byteIndex | int | Posun cílového bufferu. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |

### Návratová hodnota

Počet zapsaných bajtů.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metoda


Získá bajty, které jsou výsledkem kódování bufferu.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znaky k zakódování. |
| charCount | int | Délka zdrojového pole. |
| bytes | **uint8_t** * | Cílový buffer bajtů. |
| byteCount | int | Velikost cílového bufferu. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |

### Návratová hodnota

Počet zapsaných bajtů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)