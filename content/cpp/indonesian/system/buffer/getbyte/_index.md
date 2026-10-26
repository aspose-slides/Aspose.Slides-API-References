---
title: GetByte()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan mengambil nilai byte pada offset byte yang ditentukan.
type: docs
weight: 27
url: /id/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) Metode


Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan mengambil nilai byte pada offset byte yang ditentukan.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | The target array |
| index | int | Offset berbasis nol dari byte yang akan diambil |

### Nilai Kembali

Nilai byte pada indeks yang ditentukan

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) Metode


Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan mengambil nilai byte pada offset byte yang ditentukan.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array view |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | The target array view |
| index | int | Offset berbasis nol dari byte yang akan diambil |

### Nilai Kembali

Nilai byte pada indeks yang ditentukan

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) Metode


Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan mengambil nilai byte pada offset byte yang ditentukan.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | The target stack array |
| index | int | Offset berbasis nol dari byte yang akan diambil |

### Nilai Kembali

Nilai byte pada indeks yang ditentukan

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Array](../../array/)
* Kelas [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)