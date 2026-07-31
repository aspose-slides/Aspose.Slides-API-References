---
title: StaticCast()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan static cast pada objek SmartPtr.
type: docs
weight: 2562
url: /id/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) fungsi

Melakukan static cast pada objek [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Nilai Kembali

Hasil cast jika cast diperbolehkan.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::StaticCast(WeakPtr\<TFrom\> const\&) fungsi

Melakukan static cast pada objek [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Source pointer. |

### Nilai Kembali

Hasil cast jika cast diperbolehkan.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::StaticCast(std::nullptr_t) fungsi

Melakukan static cast pada objek null.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Target pointee type. |

### Nilai Kembali

nullptr.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::StaticCast(TFrom) fungsi

Spesialisasi untuk tipe aritmetika.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) fungsi

Proses cast dari [String](../string/) ke [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) fungsi

Spesialisasi untuk tipe aritmetika.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) fungsi

Melakukan static cast pada objek non-pointer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const TFrom\& | Source object. |

### Nilai Kembali

Hasil cast jika cast diperbolehkan.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::StaticCast(const TFrom\&) fungsi

Melakukan static cast pada objek Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Nilai Kembali

Hasil cast jika cast diperbolehkan.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::StaticCast(SmartPtr\<TFrom\>) fungsi

Melakukan static cast pada Objects ke objek Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Nilai Kembali

Hasil cast jika cast diperbolehkan.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Kelas [WeakPtr](../weakptr/)
* Kelas [String](../string/)
* Kelas [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Struktur [IsSmartPtr](../issmartptr/)
* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)