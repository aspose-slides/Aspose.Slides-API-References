---
title: AsCast()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator 'as'. Digunakan ketika diperlukan cast mirip konstruktor sederhana.
type: docs
weight: 2640
url: /id/system/ascast/
---
## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan ketika diperlukan cast mirip konstruktor sederhana.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan ketika tipe sumber dan tipe hasil sama.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk pembungkus pengecualian.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk meng-cast objek ke pengecualian.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan ketika sumber dan hasil keduanya merupakan smart pointer.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan ketika sumber dan hasil keduanya merupakan smart pointer (dengan SmartPtr<...> eksplisit pada tipe hasil).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk unboxing objek ke nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast. Mengembalikan nullable kosong jika tidak ada konversi yang tersedia.

## System::AsCast(const Source\&) fungsi

Unboxing tidak valid ke tipe non-objek.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Selalu mengembalikan null.

## System::AsCast(const Source\&) fungsi

Unboxing tidak valid ke tipe non-objek.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Selalu mengembalikan null.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk boxing objek nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk boxing objek umum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk boxing objek umum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk unboxing string.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk kasus nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast.

## System::AsCast(const Source\&) fungsi

Mengkonversi tipe sumber ke tipe hasil menggunakan cast operator ‘as’. Digunakan untuk meng-cast antar array.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) untuk di-cast. |

### Nilai Kembali

Hasil cast. Mengembalikan nullptr jika tidak ada konversi untuk anggota array manapun yang tersedia.

## Lihat Juga

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)