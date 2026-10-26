---
title: GetBytes()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Získá bajty, které jsou výsledkem kódování bufferu.
type: docs
weight: 53
url: /cs/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Získá bajty, které jsou výsledkem kódování bufferu.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |
| charIndex | int | Posun zdrojového pole. |
| charCount | int | Délka podpole zdroje. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Cílový buffer bajtů. |
| byteIndex | int | Posun cílového bufferu. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |

### Návratová hodnota

Počet zapsaných bajtů.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Získá bajty, které jsou výsledkem kódování bufferu.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argumenty

| Parameter | Type | Description |
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
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)