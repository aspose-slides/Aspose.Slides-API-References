---
title: Fallback()
second_title: Aspose.Slides for C++ API Referansı
description: Kodlama hatasını yönetir.
type: docs
weight: 27
url: /tr/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) metodu


Kodlama hatasını yönetir.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Bilinmeyen karakterler; yok sayılır. |
| index | int | Bilinmeyen karakterlerin ofseti; yok sayılır. |

### Dönüş Değeri

Asla geri dönmez, bunun yerine bir istisna fırlatır.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) metodu


Kodlama hatasını yönetir.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | Hata oluşturan surrogate çiftinin yüksek kısmı. |
| charUnknownLow | char_t | Hata oluşturan surrogate çiftinin düşük kısmı. |
| index | int | Bilinmeyen karakter ofseti; yok sayılır. |

### Dönüş Değeri

Asla geri dönmez, bunun yerine bir istisna fırlatır.

## Ayrıca Bakınız

* Sınıf [EncoderExceptionFallbackBuffer](../)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)