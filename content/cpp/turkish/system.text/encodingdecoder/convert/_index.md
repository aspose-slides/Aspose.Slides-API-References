---
title: Convert()
second_title: Aspose.Slides için C++ API Referansı
description: Baytları karakterlere dönüştürür.
type: docs
weight: 1
url: /tr/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

Baytları karakterlere dönüştürür.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | Kod çözülecek baytlar. |
| byteCount | int | Giriş tamponunun boyutu. |
| chars | char_t * | Hedef karakter tamponu. |
| charCount | int | Hedef dizi boyutu. |
| flush | **bool** | true ise, hesaplamadan sonra dahili çözücü durumunu temizler. |
| bytesUsed | int\& | Okunan bayt sayısını saklamak için değişkene referans. |
| charsUsed | int\& | Yazılan karakter sayısını saklamak için değişkene referans. |
| completed | **bool**\& | Giriş tamponu tükendiğinde true, aksi takdirde false olarak ayarlanacak değişkene referans. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

Baytları karakterlere dönüştürür.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kod çözülecek baytlar. |
| byteIndex | int | Giriş tamponunun konumu. |
| byteCount | int | Giriş tamponunun boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi konumu. |
| charCount | int | Hedef dizi boyutu. |
| flush | **bool** | true ise, hesaplamadan sonra dahili çözücü durumunu temizler. |
| bytesUsed | int\& | Okunan bayt sayısını saklamak için değişkene referans. |
| charsUsed | int\& | Yazılan karakter sayısını saklamak için değişkene referans. |
| completed | **bool**\& | Giriş tamponu tükendiğinde true, aksi takdirde false olarak ayarlanacak değişkene referans. |

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [EncodingDecoder](../)
* Ad Alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)