---
title: Cast()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika tipe sumber dan tipe hasil sama.
type: docs
weight: 14
url: /id/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) function

Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika tipe sumber dan tipe hasil sama.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Nilai kembali

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika tipe sumber dapat di-cast secara statis ke tipe hasil.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Nilai kembali

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika tipe tidak sama dan tipe sumber tidak dapat di-cast secara statis ke tipe hasil.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Nilai kembali

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika tipe sumber dibungkus ke instansi kelas [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Nilai kembali

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika tipe sumber dikeluarkan dari pembungkus (unboxed) dari instansi kelas [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Nilai kembali

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika tipe sumber dibungkus ke instansi kelas [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Nilai kembali

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika tipe sumber dikeluarkan dari pembungkus (unboxed) dari instansi kelas [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Nilai kembali

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Mengubah tipe sumber menjadi tipe hasil. Digunakan ketika casting tidak valid atau konversi bersifat eksplisit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Nilai kembali

The cast result.

## Lihat Juga

* Struktur [CastType](../casttype/)
* Ruang nama [System::Collections::Generic::Details::CastRules](../)
* Pustaka [Aspose.Slides](../../)