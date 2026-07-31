---
title: AsSpan()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat span dari sebuah array.
type: docs
weight: 1
url: /id/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) fungsi

Membuat span dari sebuah array.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam array. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Array sumber. |
| start | **int32_t** | Indeks awal dalam array. |
| length | **int32_t** | Panjang span. |

### Nilai Kembalian

Span<T> yang mencakup bagian yang ditentukan dari array.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) fungsi

Membuat span hanya-baca dari sebuah string.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | String sumber. |
| start | **int32_t** | Indeks awal dalam string. |
| length | **int32_t** | Panjang span. |

### Nilai Kembalian

ReadOnlySpan<char16_t> yang mencakup bagian yang ditentukan dari string.

## Lihat Juga

* Typedef [ArrayPtr](../../system/arrayptr/)
* Kelas [Span](../../system/span/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [String](../../system/string/)
* Ruang Nama [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)