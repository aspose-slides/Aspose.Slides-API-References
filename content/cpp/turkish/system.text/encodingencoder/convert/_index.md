---
title: Convert()
second_title: Aspose.Slides for C++ API Referansı
description: Karakterleri baytlara dönüştürür.
type: docs
weight: 1
url: /tr/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int&, int&, bool&) metodu


Characters to bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlamak için karakterler. |
| charCount | int | Giriş tamponunun boyutu. |
| bytes | **uint8_t** * | Hedef bayt tamponu. |
| byteCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kodlayıcı durumunu temizler. |
| charsUsed | int& | Okunan karakter sayısını saklamak için değişken referansı. |
| bytesUsed | int& | Yazılan bayt sayısını saklamak için değişken referansı. |
| completed | **bool**& | Giriş tamponu tükenmişse doğru, aksi halde yanlış olarak ayarlanacak değişken referansı. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int&, int&, bool&) metodu


Characters to bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlamak için karakterler. |
| charIndex | int | Giriş tamponu ofseti. |
| charCount | int | Giriş tamponunun boyutu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hedef bayt tamponu. |
| byteIndex | int | Hedef dizi ofseti. |
| byteCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kodlayıcı durumunu temizler. |
| charsUsed | int& | Okunan karakter sayısını saklamak için değişken referansı. |
| bytesUsed | int& | Yazılan bayt sayısını saklamak için değişken referansı. |
| completed | **bool**& | Giriş tamponu tükenmişse doğru, aksi halde yanlış olarak ayarlanacak değişken referansı. |

## Aynı zamanda Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [EncodingEncoder](../)
* İsim Uzayı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)