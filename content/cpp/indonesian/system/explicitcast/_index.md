---
title: ExplicitCast()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan ketika tipe sumber dan tipe hasil sama.
type: docs
weight: 2627
url: /id/system/explicitcast/
---
## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan ketika tipe sumber dan tipe hasil sama.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan ketika diperlukan cast sederhana mirip konstruktor.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk pembungkus pengecualian.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk meng-cast objek ke pengecualian.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan ketika sumber dan hasil keduanya pointer pintar (tanpa SmartPtr<...> eksplisit pada tipe hasil).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(Source) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan ketika melakukan cast pointer mentah ke pointer pintar.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | Source | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan ketika sumber dan hasil keduanya pointer pintar (dengan SmartPtr<...> eksplisit pada tipe hasil).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk meng-unboxing objek menjadi nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk membungkus nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk meng-unboxing objek nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk membungkus enum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk menyalin tipe nilai ke heap ketika tipe nilai harus direferensikan sebagai pointer pintar (dalam generik yang dibatasi dengan tipe antarmuka tetapi khusus dengan struktur yang mengimplementasikan antarmuka ini).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk mendapatkan antarmuka dari tipe nilai.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk boxing umum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk [System::String](../string/) boxing.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk meng-unboxing antarmuka.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk unboxing umum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk cast nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## System::ExplicitCast(const Source&) fungsi


Melakukan cast tipe sumber ke tipe hasil menggunakan cast eksplisit. Digunakan untuk cast antar array.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Source | Tipe sumber. |
| Result | Tipe hasil. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const Source& | [Object](../object/) untuk melakukan cast. |

### Nilai Kembali

Hasil cast.

## Lihat Juga

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)