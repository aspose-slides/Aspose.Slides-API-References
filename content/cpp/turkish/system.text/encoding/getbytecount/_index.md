---
title: GetByteCount()
second_title: Aspose.Slides for C++ API Referansı
description: Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.
type: docs
weight: 235
url: /tr/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) yöntemi

Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter tamponu. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Dönüş Değeri

Gerekli tampon boyutu.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) yöntemi

Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Karakter tamponu. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Dönüş Değeri

Gerekli tampon boyutu.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) yöntemi

Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Karakter tamponu. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Dönüş Değeri

Gerekli tampon boyutu.

## Encoding::GetByteCount(const String\&) yöntemi

Bir dizeyi kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) kodlamak için. |

### Dönüş Değeri

Gerekli tampon boyutu.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) yöntemi

Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter tamponu. |

### Dönüş Değeri

Gerekli tampon boyutu.

## Encoding::GetByteCount(const char_t *, int) yöntemi

Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Karakter tamponu. |
| count | int | [Buffer](../../../system/buffer/) boyut. |

### Dönüş Değeri

Gerekli tampon boyutu.

## Diğer Bilgiler

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Encoding](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)