---
title: StaticCastArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan casting elemen array yang ditentukan ke tipe yang berbeda. Menimpa untuk kasus di mana From adalah objek SmartPtr.
type: docs
weight: 2978
url: /id/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function


Melakukan casting elemen array yang ditentukan ke tipe yang berbeda. Menimpa untuk kasus di mana From adalah [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| To | Tipe untuk meng-cast elemen array yang ditentukan |
| From | Tipe elemen dari elemen array yang akan di-cast |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Shared pointer ke array yang berisi elemen yang akan di-cast |

### Nilai Kembali

Pointer ke array baru yang berisi elemen tipe **To** yang setara dengan elemen **from**

Usang
:   Ditambahkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function


Melakukan casting elemen array yang ditentukan ke tipe yang berbeda. Menimpa untuk kasus di mana From adalah Boxable dan To adalah [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| To | Tipe untuk meng-cast elemen array yang ditentukan |
| From | Tipe elemen dari elemen array yang akan di-cast |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Shared pointer ke array yang berisi elemen yang akan di-cast |

### Nilai Kembali

Pointer ke array baru yang berisi elemen tipe **To** yang setara dengan elemen **from**

Usang
:   Ditambahkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Kelas [Array](../array/)
* Kelas [Object](../object/)
* Struktur [IsSmartPtr](../issmartptr/)
* Struktur [IsBoxable](../isboxable/)
* Namespace [System](../)
* Pustaka [Aspose.Slides](../../)