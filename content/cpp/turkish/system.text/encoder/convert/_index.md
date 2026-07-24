---
title: Convert()
second_title: Aspose.Slides for C++ API Referansı
description: Karakterleri baytlara dönüştürür.
type: docs
weight: 79
url: /tr/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

Karakterleri baytlara dönüştürür.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlamak için karakterler. |
| charIndex | int | Girdi tamponu offset'i. |
| charCount | int | Girdi tamponu boyutu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hedef bayt tamponu. |
| byteIndex | int | Hedef dizi offset'i. |
| byteCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kodlayıcı durumunu temizler. |
| charsUsed | int\& | Okunan karakter sayısını saklamak için değişkene referans. |
| bytesUsed | int\& | Yazılan bayt sayısını saklamak için değişkene referans. |
| completed | **bool**\& | Girdi tamponu tükenmişse doğru, aksi takdirde yanlış olarak ayarlanacak değişkene referans. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

Karakterleri baytlara dönüştürür.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlamak için karakterler. |
| charCount | int | Girdi tamponu boyutu. |
| bytes | **uint8_t** * | Hedef bayt tamponu. |
| byteCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kodlayıcı durumunu temizler. |
| charsUsed | int\& | Okunan karakter sayısını saklamak için değişkene referans. |
| bytesUsed | int\& | Yazılan bayt sayısını saklamak için değişkene referans. |
| completed | **bool**\& | Girdi tamponu tükenmişse doğru, aksi takdirde yanlış olarak ayarlanacak değişkene referans. |

## Diğer Bağlantılar

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)