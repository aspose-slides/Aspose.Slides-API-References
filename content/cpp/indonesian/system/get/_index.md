---
title: Get()
second_title: Aspose.Slides untuk Referensi API C++
description: Fungsi untuk mendapatkan elemen ke-N dari tuple yang diberikan. Overload untuk objek dasar.
type: docs
weight: 2406
url: /id/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) fungsi


Fungsi untuk mendapatkan elemen ke-N dari tuple yang diberikan. Overload untuk objek dasar.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| N | indeks elemen. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | objek yang akan diperiksa. |

### Nilai Kembalian

nilai elemen ke-N dari tuple yang dikast ke objek.

## System::Get(const T\&) fungsi


Fungsi untuk mendapatkan elemen ke-N dari tuple yang diberikan. Overload untuk objek dengan metode Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| N | indeks elemen. |
| T | tipe objek yang diperiksa. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| object | const T\& | objek yang akan diperiksa. |

### Nilai Kembalian

nilai elemen ke-N dari tuple.

## System::Get(const SharedPtr\<T\>\&) fungsi


Fungsi untuk mendapatkan elemen ke-N dari tuple yang diberikan. Overload untuk shared pointer.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| N | indeks elemen. |
| T | tipe objek yang diperiksa. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | objek yang akan diperiksa. |

### Nilai Kembalian

nilai elemen ke-N dari tuple.

## System::Get(T\&, const Index\&) fungsi


Implementasi untuk ekspresi collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe koleksi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| collection | T\& | Objek koleksi. |
| index | const [Index](../index/)\& | Indeks elemen dengan tipe [System.Index](../index/). |

### Nilai Kembalian

Elemen koleksi pada offset yang dihitung.

## System::Get(T\&, const Range\&) fungsi


Mengembalikan irisan (slice) koleksi yang ditentukan oleh rentang yang diberikan.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| collection | T\& | Koleksi yang akan diiris. |
| range | const [Range](../range/)\& | Rentang yang menentukan batas irisan. |

### Nilai Kembalian

Tampilan atau irisan koleksi mulai dari offset awal yang dihitung dan panjangnya.

## System::Get(const ValueTuple\<Args...\>\&) fungsi


Mendapatkan elemen ke-N dari tuple nilai.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| N | indeks elemen. |
| Args | elemen tuple. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | tuple untuk mengambil elemen. |

### Nilai Kembalian

nilai elemen ke-N dari tuple.

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Index](../index/)
* Class [Range](../range/)
* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)