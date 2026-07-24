---
title: Fallback()
second_title: Aspose.Slides for C++ API Referansı
description: Gerçek geri dönüş prosedürünü uygular.
type: docs
weight: 14
url: /tr/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metot

Gerçek geri dönüş prosedürünü uygular.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) bayt sayısı, çözücünün çözemediği baytı da içerir. |
| index | int | [Index](../../../system/index/) hatayı tetikleyen bayt. |

### Dönüş Değeri

True, tampon bilinmeyen baytları işliyorsa, false ise yok sayıyorsa.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [DecoderFallbackBuffer](../)
* İsim Alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)