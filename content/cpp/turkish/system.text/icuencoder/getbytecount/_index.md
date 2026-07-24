---
title: GetByteCount()
second_title: Aspose.Slides for C++ API Referansı
description: Bir tamponu kodlamak için gerekli bayt sayısını alır.
type: docs
weight: 40
url: /tr/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metod


Bir tamponu kodlamak için gereken bayt sayısını alır.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlanacak karakterler. |
| index | int | [Buffer](../../../system/buffer/) ofset. |
| count | int | Kodlanacak karakter sayısı. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kodlayıcı durumunu temizler. |

### Dönüş Değeri

Tamponu kodlamak için gereken bayt sayısı.

## ICUEncoder::GetByteCount(const char_t *, int, bool) metod


Bir tamponu kodlamak için gereken bayt sayısını alır.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| count | int | Kodlanacak karakter sayısı. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kodlayıcı durumunu temizler. |

### Dönüş Değeri

Tamponu kodlamak için gereken bayt sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICUEncoder](../)
* Ad Alanı [System::Text](../../)
* Library [Aspose.Slides](../../../)