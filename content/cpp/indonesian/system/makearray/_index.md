---
title: MakeArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Fungsi pabrik yang membuat objek Array baru, mengisinya dengan elemen-elemen dari daftar inisialisasi yang ditentukan, dan mengembalikan penunjuk pintar yang menunjuk ke objek Array.
type: docs
weight: 2029
url: /id/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) fungsi


Fungsi pabrik yang membuat objek [Array](../array/) baru, mengisinya dengan elemen-elemen dari daftar inisialisasi yang ditentukan, dan mengembalikan penunjuk pintar yang menunjuk ke objek [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dari objek [Array](../array/) yang dibuat oleh fungsi |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Daftar inisialisasi yang berisi elemen-elemen untuk mengisi array |

### Nilai Kembali

Penunjuk pintar yang menunjuk ke objek [Array](../array/) yang dibangun

## System::MakeArray(Args\&&...) fungsi


Fungsi pabrik yang membuat objek [Array](../array/) baru dengan meneruskan argumen yang ditentukan ke konstruktornya.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dari objek [Array](../array/) yang dibuat oleh fungsi |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | Args\&&... | Argumen yang diteruskan ke konstruktor objek [Array](../array/) yang sedang dibangun |

### Nilai Kembali

Penunjuk pintar yang menunjuk ke objek [Array](../array/) yang dibangun

## System::MakeArray(Integral, Args\&&...) fungsi


Fungsi pabrik yang membuat objek [Array](../array/) baru dengan meneruskan argumen yang ditentukan ke konstruktornya.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dari objek [Array](../array/) yang dibuat oleh fungsi |
| Integral | Tipe ukuran array. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | Integral | Ukuran array yang sedang dibuat. |
| args | Args\&&... | Argumen yang diteruskan ke konstruktor objek [Array](../array/) yang sedang dibangun |

### Nilai Kembali

Penunjuk pintar yang menunjuk ke objek [Array](../array/) yang dibangun

## Lihat Juga

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)