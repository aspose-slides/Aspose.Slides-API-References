---
title: GetChars()
second_title: Aspose.Slides for C++ API Referansı
description: Bir tamponun kod çözülmesinden elde edilen karakterleri alır.
type: docs
weight: 53
url: /tr/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metot


Bir tamponun kod çözülmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çözümlemesi yapılacak baytlar. |
| byteIndex | int | Giriş tamponu ofseti. |
| byteCount | int | Giriş tamponu boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi ofseti. |

### Dönüş Değeri

Yazılan karakter sayısı.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metot


Bir tamponun kod çözülmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çözümlemesi yapılacak baytlar. |
| byteIndex | int | Giriş tamponu ofseti. |
| byteCount | int | Giriş tamponu boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi ofseti. |
| flush | **bool** | true ise, hesaplamadan sonra dahili kod çözücü durumu temizlenir. |

### Dönüş Değeri

Yazılan karakter sayısı.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) metot


Bir tamponun kod çözülmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | Çözümlemesi yapılacak baytlar. |
| byteCount | int | Giriş tamponu boyutu. |
| chars | char_t * | Hedef karakter tamponu. |
| charCount | int | Hedef dizi boyutu. |
| flush | **bool** | true ise, hesaplamadan sonra dahili kod çözücü durumu temizlenir. |

### Dönüş Değeri

Yazılan karakter sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Decoder](../)
* İsim Uzayı [System::Text](../../)
* Library [Aspose.Slides](../../../)