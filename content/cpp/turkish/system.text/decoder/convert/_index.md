---
title: Convert()
second_title: Aspose.Slides for C++ API Referansı
description: Baytları karakterlere dönüştürür.
type: docs
weight: 79
url: /tr/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) yöntemi

Baytları karakterlere dönüştürür.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kod çözülecek baytlar. |
| byteIndex | int | Girdi tamponu ofseti. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi ofseti. |
| charCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç çözücü durumunu temizler. |
| bytesUsed | int\& | Okunan bayt sayısını saklamak için değişkene referans. |
| charsUsed | int\& | Yazılan karakter sayısını saklamak için değişkene referans. |
| completed | **bool**\& | Girdi tamponu tüketildi ise true, aksi takdirde false olarak ayarlanacak değişkene referans. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) yöntemi

Baytları karakterlere dönüştürür.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | Kod çözülecek baytlar. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | char_t * | Hedef karakter tamponu. |
| charCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç çözücü durumunu temizler. |
| bytesUsed | int\& | Okunan bayt sayısını saklamak için değişkene referans. |
| charsUsed | int\& | Yazılan karakter sayısını saklamak için değişkene referans. |
| completed | **bool**\& | Girdi tamponu tüketildi ise true, aksi takdirde false olarak ayarlanacak değişkene referans. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Decoder](../)
* İsim Uzayı [System::Text](../../)
* Library [Aspose.Slides](../../../)