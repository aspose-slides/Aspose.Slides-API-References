---
title: SetByte()
second_title: Referensi API Aspose.Slides untuk C++
description: Menafsirkan array bertipe yang ditentukan sebagai array byte mentah dan menetapkan nilai byte yang ditentukan pada offset byte yang ditentukan.
type: docs
weight: 40
url: /id/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) metode

Menafsirkan array bertipe yang ditentukan sebagai array byte mentah dan menetapkan nilai byte yang ditentukan pada offset byte yang ditentukan.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dari array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Array target |
| index | int | Offset berbasis nol dari byte yang akan disetel |
| value | **uint8_t** | Nilai byte yang akan disetel |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) metode

Menafsirkan array bertipe yang ditentukan sebagai array byte mentah dan menetapkan nilai byte yang ditentukan pada offset byte yang ditentukan.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dari array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Tampilan array target |
| index | int | Offset berbasis nol dari byte yang akan disetel |
| value | **uint8_t** | Nilai byte yang akan disetel |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) metode

Menafsirkan array bertipe yang ditentukan sebagai array byte mentah dan menetapkan nilai byte yang ditentukan pada offset byte yang ditentukan.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dari array |
| N | Ukuran stack array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Stack array target |
| index | int | Offset berbasis nol dari byte yang akan disetel |
| value | **uint8_t** | Nilai byte yang akan disetel |

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Array](../../array/)
* Kelas [Buffer](../)
* Ruang nama [System](../../)
* Library [Aspose.Slides](../../../)