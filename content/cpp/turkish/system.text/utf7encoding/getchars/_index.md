---
title: GetChars()
second_title: Aspose.Slides for C++ API Referansı
description: Bir bayt tamponunun kod çözülmesinden elde edilen karakterleri alır.
type: docs
weight: 92
url: /tr/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metod

Bir bayt tamponunun kod çözülmesinden elde edilen karakterleri alır.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) baytları okumak için. |
| byte_index | int | Giriş tamponu ofseti. |
| byte_count | int | Giriş tamponu boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| char_index | int | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan karakter sayısı.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) metod

Bir bayt tamponunun kod çözülmesinden elde edilen karakterleri alır.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) baytları okumak için. |
| byte_count | int | Giriş tamponu boyutu. |
| chars | char_t * | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| char_count | int | Çıktı tamponu boyutu. |

### Dönüş Değeri

Yazılan karakter sayısı.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metod

Bir bayt tamponunun kod çözülmesinden elde edilen karakterleri alır.

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
| char_index | int | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan karakter sayısı.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metod

Bir bayt tamponunun kod çözülmesinden elde edilen karakterleri alır.

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

[Buffer](../../../system/buffer/) çözülen karakterlerin.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) metod

Bir bayt tamponunun kod çözülmesinden elde edilen karakterleri alır.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) baytları okumak için. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) çözülen karakterlerin.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) metod

Bir bayt tamponunun kod çözülmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) baytları okumak için. |
| byte_count | int | Giriş tamponu boyutu. |
| chars | char_t * | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| char_count | int | Çıktı tamponu boyutu. |

### Dönüş Değeri

Yazılan karakter sayısı.

## Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [UTF7Encoding](../)
* AdAlanı [System::Text](../../)
* Library [Aspose.Slides](../../../)