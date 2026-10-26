---
title: BlockCopy()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyalin sejumlah byte yang ditentukan dari buffer sumber ke buffer tujuan.
type: docs
weight: 1
url: /id/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) metode


Menyalin sejumlah byte yang ditentukan dari buffer sumber ke buffer tujuan.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const **uint8_t** * | Penunjuk ke buffer sumber |
| srcOffset | int | Offset byte dalam buffer sumber tempat penyalinan dimulai |
| dst | **uint8_t** * | Penunjuk ke buffer tujuan |
| dstOffset | int | Offset byte dalam buffer tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metode


Menafsirkan dua array bertipe yang ditentukan sebagai array mentah byte dan menyalin data dari salah satunya ke yang lain.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TSrc | Tipe elemen array sumber |
| TDst | Tipe elemen array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Array sumber |
| srcOffset | int | Offset byte dalam array sumber tersebut tempat penyalinan dimulai |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Array tujuan |
| dstOffset | int | Offset byte dalam array tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) metode


Menafsirkan dua array yang ditentukan sebagai array mentah byte dan menyalin data dari salah satunya ke yang lain.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Array sumber |
| srcOffset | int | Offset byte dalam array sumber tersebut tempat penyalinan dimulai |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Array tujuan |
| dstOffset | int | Offset byte dalam array tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metode


Menafsirkan dua array bertipe yang ditentukan sebagai array mentah byte dan menyalin data dari salah satunya ke yang lain.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TSrc | Tipe elemen tampilan array sumber |
| TDst | Tipe elemen tampilan array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Tampilan array sumber |
| srcOffset | int | Offset byte dalam tampilan array sumber tersebut tempat penyalinan dimulai |
| dst | const System::Details::ArrayView\<TDst\>\& | Tampilan array tujuan |
| dstOffset | int | Offset byte dalam tampilan array tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metode


Menafsirkan dua array bertipe yang ditentukan sebagai array mentah byte dan menyalin data dari salah satunya ke yang lain.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TSrc | Tipe elemen array sumber |
| TDst | Tipe elemen tampilan array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Array sumber |
| srcOffset | int | Offset byte dalam array sumber tersebut tempat penyalinan dimulai |
| dst | const System::Details::ArrayView\<TDst\>\& | Tampilan array tujuan |
| dstOffset | int | Offset byte dalam tampilan array tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metode


Menafsirkan dua array bertipe yang ditentukan sebagai array mentah byte dan menyalin data dari salah satunya ke yang lain.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TSrc | Tipe elemen tampilan array sumber |
| TDst | Tipe elemen array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Tampilan array sumber |
| srcOffset | int | Offset byte dalam tampilan array sumber tersebut tempat penyalinan dimulai |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Array tujuan |
| dstOffset | int | Offset byte dalam array tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metode


Menafsirkan dua array bertipe yang ditentukan sebagai array mentah byte dan menyalin data dari salah satunya ke yang lain.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TSrc | Tipe elemen array tumpukan sumber |
| NS | Ukuran array tumpukan sumber |
| TDst | Tipe elemen array tumpukan tujuan |
| ND | Ukuran array tumpukan tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Array tumpukan sumber |
| srcOffset | int | Offset byte dalam array tumpukan sumber tersebut tempat penyalinan dimulai |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Array tumpukan tujuan |
| dstOffset | int | Offset byte dalam array tumpukan tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metode


Menafsirkan dua array bertipe yang ditentukan sebagai array mentah byte dan menyalin data dari salah satunya ke yang lain.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TSrc | Tipe elemen array sumber |
| TDst | Tipe elemen array tumpukan tujuan |
| ND | Ukuran array tumpukan tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Array sumber |
| srcOffset | int | Offset byte dalam array sumber tersebut tempat penyalinan dimulai |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Array tumpukan tujuan |
| dstOffset | int | Offset byte dalam array tumpukan tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metode


Menafsirkan dua array bertipe yang ditentukan sebagai array mentah byte dan menyalin data dari salah satunya ke yang lain.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TSrc | Tipe elemen array tumpukan sumber |
| NS | Ukuran array tumpukan sumber |
| TDst | Tipe elemen array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Array tumpukan sumber |
| srcOffset | int | Offset byte dalam array tumpukan sumber tersebut tempat penyalinan dimulai |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Array tujuan |
| dstOffset | int | Offset byte dalam array tujuan tempat memulai penyisipan data |
| count | int | Jumlah byte yang akan disalin |

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Buffer](../)
* Kelas [Array](../../array/)
* Kelas [ArrayBase](../../arraybase/)
* Ruang nama [System](../../)
* Pustaka [Aspose.Slides](../../../)