---
title: GetChars()
second_title: Aspose.Slides for C++ API Referansı
description: Bir bayt tamponunun çözülmesinden elde edilen karakterleri alır.
type: docs
weight: 66
url: /tr/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metot

Bir bayt tamponunun çözülmesinden ortaya çıkan karakterleri alır.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) okunacak baytları. |
| byte_count | int | Giriş tamponu boyutu. |
| chars | char_t * | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| char_count | int | Çıktı tamponu boyutu. |

### Dönüş Değeri

Yazılan karakter sayısı.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metot

Bir bayt tamponunun çözülmesinden ortaya çıkan karakterleri alır.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) okunacak baytları. |
| byte_index | int | Giriş tamponu konumu. |
| byte_count | int | Giriş tamponu boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| char_index | int | Çıktı tamponu konumu. |

### Dönüş Değeri

Yazılan karakter sayısı.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metot

Bir bayt tamponunun çözülmesinden ortaya çıkan karakterleri alır.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) okunacak baytları. |
| index | int | Giriş tamponu konumu. |
| count | int | Giriş tamponu boyutu. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) çözülen karakter sayısı.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) metot

Bir bayt tamponunun çözülmesinden ortaya çıkan karakterleri alır.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) okunacak baytları. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) çözülen karakter sayısı.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metot

Bir bayt tamponunun çözülmesinden ortaya çıkan karakterleri alır.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) okunacak baytları. |
| byte_count | int | Giriş tamponu boyutu. |
| chars | char_t * | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| char_count | int | Çıktı tamponu boyutu. |

### Dönüş Değeri

Yazılan karakter sayısı.

## Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICUEncoding](../)
* İsim Uzayı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)