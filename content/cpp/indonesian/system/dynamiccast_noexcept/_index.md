---
title: DynamicCast_noexcept()
second_title: Referensi API Aspose.Slides untuk C++
description: Cast usang lama. Akan dihapus di versi mendatang.
type: docs
weight: 2523
url: /id/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) fungsi


Cast usang yang lama. Akan dihapus di versi mendatang.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe Exception target. |
| TFrom | Tipe Exception sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const TFrom\& | Pointer sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

## Catatan


Melakukan dynamic cast pada objek Exception. Tidak direkomendasikan
:   Dibiarkan untuk kompatibilitas mundur. Gunakan AsCast sebagai gantinya.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) fungsi


Melakukan dynamic cast pada [SmartPtr](../smartptr/) objek.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe pointee target. |
| TFrom | Tipe pointee sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Pointer sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

Tidak direkomendasikan
:   Dibiarkan untuk kompatibilitas mundur. Gunakan AsCast sebagai gantinya.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) fungsi


Melakukan dynamic cast pada Objects ke objek Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe Exception target. |
| TFrom | [Object](../object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointer sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

Tidak direkomendasikan
:   Dibiarkan untuk kompatibilitas mundur. Gunakan AsCast sebagai gantinya.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Kelas [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Pustaka [Aspose.Slides](../../)