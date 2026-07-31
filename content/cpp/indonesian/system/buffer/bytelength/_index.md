---
title: ByteLength()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan jumlah byte yang ditempati oleh semua elemen array yang ditentukan.
type: docs
weight: 14
url: /id/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) metode


Menentukan jumlah byte yang ditempati oleh semua elemen dari array yang ditentukan.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Sebuah array |

### Nilai Kembali

Jumlah byte yang ditempati oleh semua elemen dari array yang ditentukan

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) metode


Menentukan jumlah byte yang ditempati oleh semua elemen dari view array yang ditentukan.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen view array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Sebuah view array |

### Nilai Kembali

Jumlah byte yang ditempati oleh semua elemen dari view array yang ditentukan

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) metode


Menentukan jumlah byte yang ditempati oleh semua elemen dari stack array yang ditentukan.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen stack array |
| N | Ukuran stack array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Sebuah stack array |

### Nilai Kembali

Jumlah byte yang ditempati oleh semua elemen dari stack array yang ditentukan

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Array](../../array/)
* Kelas [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)