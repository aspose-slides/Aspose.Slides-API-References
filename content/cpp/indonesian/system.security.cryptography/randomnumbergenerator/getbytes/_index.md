---
title: GetBytes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengisi elemen array yang ada dengan byte acak.
type: docs
weight: 14
url: /id/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) metode

Mengisi elemen array yang ada dengan byte acak.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte untuk mengisi. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) metode

Mengisi irisan array yang ada dengan byte acak.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte untuk mengisi irisan. |
| offset | int | Indeks awal irisan. |
| count | int | Ukuran irisan. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) metode

Mengisi elemen tampilan array yang ada dengan byte acak.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Tampilan array byte untuk mengisi. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) metode

Mengisi irisan tampilan array yang ada dengan byte acak.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Tampilan array byte untuk mengisi irisan. |
| offset | int | Indeks awal irisan. |
| count | int | Ukuran irisan. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) metode

Mengisi elemen array stack yang ada dengan byte acak.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Array stack byte untuk mengisi. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) metode

Mengisi irisan array stack yang ada dengan byte acak.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Array stack byte untuk mengisi irisan. |
| offset | int | Indeks awal irisan. |
| count | int | Ukuran irisan. |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [RandomNumberGenerator](../)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)