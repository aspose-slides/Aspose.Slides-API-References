---
title: Convert()
second_title: Aspose.Slides for C++ API Referansı
description: Karakterleri baytlara dönüştürür.
type: docs
weight: 66
url: /tr/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metot


Karakterleri baytlara dönüştürür.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlanacak karakterler. |
| charIndex | int | Giriş tamponu ofseti. |
| charCount | int | Giriş tamponu boyutu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hedef bayt tamponu. |
| byteIndex | int | Hedef dizi ofseti. |
| byteCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |
| charsUsed | int\& | Okunan karakter sayısını depolamak için değişkene referans. |
| bytesUsed | int\& | Yazılan bayt sayısını depolamak için değişkene referans. |
| completed | **bool**\& | Giriş tamponu tüketildiğinde doğru, aksi takdirde yanlış olarak ayarlanacak değişkene referans. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) metot


Karakterleri baytlara dönüştürür.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| charCount | int | Giriş tamponu boyutu. |
| bytes | **uint8_t** * | Hedef bayt tamponu. |
| byteCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |
| charsUsed | int\& | Okunan karakter sayısını depolamak için değişkene referans. |
| bytesUsed | int\& | Yazılan bayt sayısını depolamak için değişkene referans. |
| completed | **bool**\& | Giriş tamponu tüketildiğinde doğru, aksi takdirde yanlış olarak ayarlanacak değişkene referans. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICUEncoder](../)
* Ad alanı [System::Text](../../)
* Library [Aspose.Slides](../../../)