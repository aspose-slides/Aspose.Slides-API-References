---
title: GetBytes()
second_title: Aspose.Slides for C++ API Referansı
description: Bir tamponu kodlayarak ortaya çıkan baytları alın.
type: docs
weight: 53
url: /tr/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metod

Kodlama işlemi sonucunda oluşan baytları alın.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlanacak karakterler. |
| charIndex | int | Kaynak dizi ofseti. |
| charCount | int | Kaynak alt dizi uzunluğu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hedef bayt tamponu. |
| byteIndex | int | Hedef tampon ofseti. |
| flush | **bool** | **true** ise hesaplamadan sonra iç kodlayıcı durumu temizlenir. |

### Dönüş Değeri

Yazılan baytların sayısı.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metod

Kodlama işlemi sonucunda oluşan baytları alın.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| charCount | int | Kaynak dizi uzunluğu. |
| bytes | **uint8_t** * | Hedef bayt tamponu. |
| byteCount | int | Hedef tampon boyutu. |
| flush | **bool** | **true** ise hesaplamadan sonra iç kodlayıcı durumu temizlenir. |

### Dönüş Değeri

Yazılan baytların sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICUEncoder](../)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)