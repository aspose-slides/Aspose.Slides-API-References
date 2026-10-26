---
title: GetChars()
second_title: Aspose.Slides for C++ API Referansı
description: Bir bayt tamponunun çözümlenmesinden elde edilen karakterleri alır.
type: docs
weight: 274
url: /tr/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) yöntemi

Bir bayt tamponunun çözümlenmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) baytları okumak için. |
| byte_index | int | Giriş tamponu ofseti. |
| byte_count | int | Giriş tamponu boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| char_index | int | Çıkış tamponu ofseti. |

### Dönüş Değeri

Yazılan karakter sayısı.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) yöntemi

Bir bayt tamponunun çözümlenmesinden elde edilen karakterleri alır.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) baytları okumak için. |
| index | int | Giriş tamponu ofseti. |
| count | int | Giriş tamponu boyutu. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) çözülmüş karakterlerin.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) yöntemi

Bir bayt tamponunun çözümlenmesinden elde edilen karakterleri alır.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) baytları okumak için. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) çözülmüş karakterlerin.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) yöntemi

Bir bayt tamponunun çözümlenmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) baytları okumak için. |
| byte_count | int | Giriş tamponu boyutu. |
| chars | char_t * | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| char_count | int | Çıkış tamponu boyutu. |

### Dönüş Değeri

Yazılan karakter sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Encoding](../)
* İsim Uzayı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)