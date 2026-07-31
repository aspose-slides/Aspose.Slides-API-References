---
title: DynamicCast()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan cast dinamis pada objek Exception.
type: docs
weight: 2536
url: /id/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) fungsi

Melakukan cast dinamis pada objek Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| TTo | Tipe Exception target. |
| TFrom | Tipe Exception sumber. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Penunjuk sumber. |

### Nilai Kembali

Hasil cast jika cast diizinkan.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) fungsi

Melakukan cast dinamis pada objek [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| TTo | Tipe yang ditunjuk target. |
| TFrom | Tipe yang ditunjuk sumber. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Penunjuk sumber. |

### Nilai Kembali

Hasil cast jika cast diizinkan.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::DynamicCast(SmartPtr\<TFrom\>) fungsi

Membongkar enum yang dibungkus melalui cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| TTo | Tipe enum target. |
| TFrom | Tipe yang ditunjuk sumber. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Penunjuk ke objek untuk membongkar data. |

### Nilai Kembali

Nilai enum yang telah dibongkar.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::DynamicCast(std::nullptr_t) fungsi

Melakukan cast dinamis pada objek null.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| TTo | Tipe yang ditunjuk target. |

### Nilai Kembali

nullptr.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::DynamicCast(TFrom\&) fungsi

Melakukan cast dinamis pada objek non-pointer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| TTo | Tipe target. |
| TFrom | Tipe sumber. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | Objek sumber. |

### Nilai Kembali

Hasil cast.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::DynamicCast(SmartPtr\<TFrom\>) fungsi

Melakukan cast dinamis pada Objects menjadi objek Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| TTo | Tipe Exception target. |
| TFrom | Tipe [Object](../object/). |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Penunjuk sumber. |

### Nilai Kembali

Hasil cast jika cast diizinkan.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## System::DynamicCast(TFrom) fungsi

Melakukan cast dinamis dari IntPtr ke pointer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| TTo | Tipe target. |
| TFrom | Tipe sumber. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | Nilai IntPtr sumber. |

### Nilai Kembali

Hasil cast.

Usang
:   Dibiarkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Kelas [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Struktur [IsSmartPtr](../issmartptr/)
* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)