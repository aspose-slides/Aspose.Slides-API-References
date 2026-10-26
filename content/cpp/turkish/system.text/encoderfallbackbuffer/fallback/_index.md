---
title: Fallback()
second_title: Aspose.Slides for C++ API Referansı
description: Gerçek geri dönüş prosedürünü uygular.
type: docs
weight: 14
url: /tr/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) metodu

Gerçek geri dönüş prosedürünü uygular.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charUnknown | char_t | Karakter kodlayıcı kodlamayı başaramaz. |
| index | int | [Index](../../../system/index/) hatayı tetikleyen karakterin. |

### Dönüş Değeri

Tampon, bilinmeyen karakterleri işlerse true, aksi takdirde false döner.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) metodu

Gerçek geri dönüş prosedürünü uygular.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charUnknownHigh | char_t | Hata tetikleyen surrogate çiftinin yüksek kısmı. |
| charUnknownLow | char_t | Hata tetikleyen surrogate çiftinin düşük kısmı. |
| index | int | [Index](../../../system/index/) hatayı tetikleyen karakterin. |

### Dönüş Değeri

Tampon, bilinmeyen karakterleri işlerse true, aksi takdirde false döner.

## İlgili

* Sınıf [EncoderFallbackBuffer](../)
* İsim Uzayı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)