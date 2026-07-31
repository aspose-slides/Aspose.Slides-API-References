---
title: CanCast()
second_title: Aspose.Slides untuk Referensi API C++
description: Memeriksa kemungkinan cast.
type: docs
weight: 40
url: /id/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) fungsi

Memeriksa kemungkinan cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Nilai Kembalian

True ketika nilai non nullptr dikembalikan setelah casting, jika tidak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fungsi

Memeriksa kemungkinan cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Nilai Kembalian

True ketika nilai non nullptr dikembalikan setelah casting, jika tidak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fungsi

Memeriksa kemungkinan cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Nilai Kembalian

True ketika nilai non nullptr dikembalikan setelah casting, jika tidak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fungsi

Memeriksa kemungkinan cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Nilai Kembalian

Selalu mengembalikan true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fungsi

Memeriksa kemungkinan cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Nilai Kembalian

True ketika nilai non nullptr dikembalikan setelah casting, jika tidak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fungsi

Memeriksa kemungkinan cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Nilai Kembalian

Selalu mengembalikan true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fungsi

Memeriksa kemungkinan cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Nilai Kembalian

True jika operasi cast berhasil dilakukan, jika tidak false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fungsi

Memeriksa kemungkinan cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Nilai Kembalian

Selalu mengembalikan false.

## Lihat Juga

* Struct [CastType](../casttype/)
* Ruang nama [System::Collections::Generic::Details::CastRules](../)
* Pustaka [Aspose.Slides](../../)