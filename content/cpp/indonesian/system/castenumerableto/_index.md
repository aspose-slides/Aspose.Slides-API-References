---
title: CastEnumerableTo()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan casting eksplisit elemen objek enumerable yang ditentukan ke tipe yang berbeda.
type: docs
weight: 2965
url: /id/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) fungsi


Melakukan casting eksplisit elemen objek enumerable yang ditentukan ke tipe yang berbeda.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| To | Tipe yang akan di-cast secara statis elemen objek enumerable ke |
| From | Tipe objek enumerable |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| enumerable | const From\& | Objek enumerable yang berisi elemen yang akan di-cast |

### Nilai Kembalian

Pointer ke koleksi baru yang berisi elemen bertipe **To** yang setara dengan elemen **enumerable**

## System::CastEnumerableTo(const From\&) fungsi


Melakukan casting eksplisit elemen objek enumerable yang ditentukan ke tipe yang berbeda.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| To | Tipe yang akan di-cast secara statis elemen objek enumerable ke |
| From | Tipe objek enumerable |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| enumerable | const From\& | adalah turunan dari objek Enumerable dengan metode get_Count yang didefinisikan dan berisi elemen yang akan di-cast |

### Nilai Kembalian

Pointer ke koleksi baru yang berisi elemen bertipe **To** yang setara dengan elemen **enumerable**

## Lihat Juga

* Kelas [ListPtr](../../system.collections.generic/listptr/)
* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)