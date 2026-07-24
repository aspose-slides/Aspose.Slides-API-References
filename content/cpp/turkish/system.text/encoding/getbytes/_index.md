---
title: GetBytes()
second_title: Aspose.Slides for C++ API Referansı
description: Bir karakter tamponunu kodlayarak ortaya çıkan baytları alır.
type: docs
weight: 248
url: /tr/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlanacak karakterler. |
| char_index | int | Karakter diliminin başlangıcı. |
| char_count | int | Dönüştürülecek karakter sayısı. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| byte_index | int | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan bayt sayısı.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Kodlanacak karakterler. |
| char_index | int | Karakter diliminin başlangıcı. |
| char_count | int | Dönüştürülecek karakter sayısı. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| byte_index | int | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan bayt sayısı.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Kodlanacak karakterler. |
| char_index | int | Karakter diliminin başlangıcı. |
| char_count | int | Dönüştürülecek karakter sayısı. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| byte_index | int | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan bayt sayısı.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) kodlamak için. |
| char_index | int | Karakter diliminin başlangıcı. |
| char_count | int | Dönüştürülecek karakter sayısı. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| byte_index | int | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan bayt sayısı.

## Encoding::GetBytes(const String\&) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) kodlamak için. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) kodlanan karakterlerin temsili tutan.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlanacak karakterler. |
| index | int | Karakter diliminin başlangıcı. |
| count | int | Dönüştürülecek karakter sayısı. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) kodlanan karakterlerin temsili tutan.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Kodlanacak karakterler. |
| index | int | Karakter diliminin başlangıcı. |
| count | int | Dönüştürülecek karakter sayısı. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) kodlanan karakterlerin temsili tutan.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Kodlanacak karakterler. |
| index | int | Karakter diliminin başlangıcı. |
| count | int | Dönüştürülecek karakter sayısı. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) kodlanan karakterlerin temsili tutan.

## Encoding::GetBytes(ArrayPtr\<char_t\>) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlanacak karakterler. |

### Dönüş Değeri

[Buffer](../../../system/buffer/) kodlanan karakterlerin temsili tutan.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) metod

Karakter tamponunu kodlayarak ortaya çıkan baytları alır.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| char_count | int | Dönüştürülecek karakter sayısı. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) karakterleri koymak için. |
| byte_count | int | Çıktı tamponu boyutu. |

### Dönüş Değeri

Yazılan bayt sayısı.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Encoding](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)