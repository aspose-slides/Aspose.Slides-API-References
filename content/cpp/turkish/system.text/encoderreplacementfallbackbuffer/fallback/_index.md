---
title: Fallback()
second_title: Aspose.Slides for C++ API Referansı
description: Kodlama hatasını işler.
type: docs
weight: 27
url: /tr/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) metod

Kodlama hatasını işler.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charUnknown | char_t | Bilinmeyen karakter; yok sayıldı. |
| index | int | Bilinmeyen karakter konumu; yok sayıldı. |

### Dönüş Değeri

Doğru eğer yerine koyma dizesi sağlanmış ve boş değilse, aksi takdirde yanlış.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) metod

Kodlama hatasını işler.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charUnknownHigh | char_t | Hata tetikleyen surrogate çiftinin yüksek kısmı. |
| charUnknownLow | char_t | Hata tetikleyen surrogate çiftinin düşük kısmı. |
| index | int | Bilinmeyen karakter konumu; yok sayıldı. |

### Dönüş Değeri

Doğru eğer yerine koyma dizesi sağlanmış ve boş değilse, aksi takdirde yanlış.

## Ayrıca Bakınız

* Sınıf [EncoderReplacementFallbackBuffer](../)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)