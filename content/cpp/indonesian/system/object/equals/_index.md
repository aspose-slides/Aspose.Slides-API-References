---
title: Equals()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan objek menggunakan semantik C# Object.Equals.
type: docs
weight: 157
url: /id/system/object/equals/
---
## Object::Equals(ptr) metode


Membandingkan objek menggunakan semantik C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) untuk dibandingkan dengan yang saat ini. |

### Nilai Kembali

True jika objek dianggap sama dan false jika tidak.

## Object::Equals(T1 const\&, T2 const\&) metode


Membandingkan objek tipe referensi dalam gaya C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe objek pertama untuk dibandingkan. |
| T2 | Tipe objek kedua untuk dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objA | T1 const\& | Objek pertama untuk dibandingkan. |
| objB | T2 const\& | Objek kedua untuk dibandingkan. |

### Nilai Kembali

True jika objek cocok baik melalui referensi atau secara semantik (dengan perbandingan mirip [Object.Equals](./)), false jika tidak.

## Object::Equals(T1 const\&, T2 const\&) metode


Membandingkan objek tipe nilai dalam gaya C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe objek pertama untuk dibandingkan. |
| T2 | Tipe objek kedua untuk dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objA | T1 const\& | Objek pertama untuk dibandingkan. |
| objB | T2 const\& | Objek kedua untuk dibandingkan. |

### Nilai Kembali

True jika objek dianggap sama oleh operator kesetaraan yang tersedia, false jika tidak.

## Object::Equals(float const\&, float const\&) metode


Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objA | **float** const\& | Nilai titik mengambang LHS. |
| objB | **float** const\& | Nilai titik mengambang RHS. |

### Nilai Kembali

True jika **objA** dan **objB** keduanya NaN atau sama, false jika tidak.

## Object::Equals(double const\&, double const\&) metode


Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objA | **double** const\& | Nilai titik mengambang LHS. |
| objB | **double** const\& | Nilai titik mengambang RHS. |

### Nilai Kembali

True jika **objA** dan **objB** keduanya NaN atau sama, false jika tidak.

## Lihat Juga

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)