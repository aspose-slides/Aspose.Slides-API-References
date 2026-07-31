---
title: GetString()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendekode buffer byte menjadi string.
type: docs
weight: 313
url: /id/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) metode

Mendekode buffer byte menjadi string.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) untuk membaca byte dari. |
| byte_count | int | Ukuran buffer input. |

### Nilai Kembali

[String](../../../system/string/) karakter terdekode.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) metode

Mendekode buffer byte menjadi string.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) untuk membaca byte dari. |

### Nilai Kembali

[String](../../../system/string/) karakter terdekode.

## Encoding::GetString(ArrayPtr\<uint8_t\>) metode

Mendekode buffer byte menjadi string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca byte dari. |

### Nilai Kembali

[String](../../../system/string/) karakter terdekode.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) metode

Mendekode buffer byte menjadi string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) untuk membaca byte dari. |

### Nilai Kembali

[String](../../../system/string/) karakter terdekode.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) metode

Mendekode buffer byte menjadi string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) untuk membaca byte dari. |

### Nilai Kembali

[String](../../../system/string/) karakter terdekode.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) metode

Mendekode buffer byte menjadi string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca byte dari. |
| index | int | Offset buffer input. |
| count | int | Ukuran buffer input. |

### Nilai Kembali

[String](../../../system/string/) karakter terdekode.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) metode

Mendekode buffer byte menjadi string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) untuk membaca byte dari. |
| index | int | Offset buffer input. |
| count | int | Ukuran buffer input. |

### Nilai Kembali

[String](../../../system/string/) karakter terdekode.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) metode

Mendekode buffer byte menjadi string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) untuk membaca byte dari. |
| index | int | Offset buffer input. |
| count | int | Ukuran buffer input. |

### Nilai Kembali

[String](../../../system/string/) karakter terdekode.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [Encoding](../)
* Kelas [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)