---
title: HasOperatorEqualsHelper()
second_title: Referensi API Aspose.Slides untuk C++
description: Fungsi pembantu untuk menentukan apakah kelas tertentu memiliki operator ==.
type: docs
weight: 235
url: /id/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) function


Fungsi pembantu untuk menentukan apakah kelas tertentu memiliki operator ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang diperiksa. |
| Dummy | Argumen dummy untuk sihir SFINAE. |

### Nilai Kembali

Nilai std::true_type jika operator == ada dan false jika tidak.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) function


Fungsi pembantu untuk menentukan apakah kelas tertentu memiliki operator ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```


### Nilai Kembali

Nilai std::true_type jika operator == ada dan false jika tidak.

## Lihat Juga

* Ruang nama [System::Collections::Generic::Details](../)
* Pustaka [Aspose.Slides](../../)