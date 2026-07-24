---
title: GetBytes()
second_title: Aspose.Slides için C++ API Referansı
description: Bir tamponun kodlanmasından elde edilen baytları alır.
type: docs
weight: 53
url: /tr/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metod


Bir tamponun kodlanmasından elde edilen baytları alır.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlanacak karakterler. |
| charIndex | int | Kaynak dizi ofseti. |
| charCount | int | Kaynak alt dizi uzunluğu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hedef bayt tamponu. |
| byteIndex | int | Hedef tampon ofseti. |
| flush | **bool** | Doğru ise, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |

### Dönüş Değeri

Yazılan bayt sayısı.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metod


Bir tamponun kodlanmasından elde edilen baytları alır.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| charCount | int | Kaynak dizi uzunluğu. |
| bytes | **uint8_t** * | Hedef bayt tamponu. |
| byteCount | int | Hedef tampon boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |

### Dönüş Değeri

Yazılan bayt sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Encoder](../)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)