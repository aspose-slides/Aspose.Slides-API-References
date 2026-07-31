---
title: StaticCast_noexcept()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan static cast pada objek SmartPtr.
type: docs
weight: 2549
url: /id/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) fungsi


Melakukan static cast pada objek [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe pointee target. |
| TFrom | Tipe pointee sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Penunjuk sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

Tidak direkomendasikan
:   Ditinggalkan untuk kompatibilitas mundur. Gunakan AsCast sebagai gantinya.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) fungsi


Melakukan static cast pada objek [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe pointee target. |
| TFrom | Tipe pointee sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Penunjuk sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

Tidak direkomendasikan
:   Ditinggalkan untuk kompatibilitas mundur. Gunakan AsCast sebagai gantinya.

## System::StaticCast_noexcept(const TFrom\&) fungsi


Melakukan static cast pada objek Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe Exception target. |
| TFrom | Tipe Exception sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const TFrom\& | Penunjuk sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

Tidak direkomendasikan
:   Ditinggalkan untuk kompatibilitas mundur. Gunakan AsCast sebagai gantinya.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) fungsi


Melakukan static cast pada Objects ke objek Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe Exception target. |
| TFrom | Tipe [Object](../object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Penunjuk sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

Tidak direkomendasikan
:   Ditinggalkan untuk kompatibilitas mundur. Gunakan AsCast sebagai gantinya.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Kelas [WeakPtr](../weakptr/)
* Kelas [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Namespace [System](../)
* Pustaka [Aspose.Slides](../../)