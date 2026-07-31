---
title: operator!=()
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 2055
url: /id/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) fungsi




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) fungsi




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) fungsi




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) fungsi


Menentukan apakah objek [Nullable](../nullable/) yang ditentukan mewakili nilai yang tidak sama dengan null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | std::nullptr_t | Referensi konstan ke objek [Nullable](../nullable/) untuk diuji |

### Nilai Kembalian

True jika objek yang ditentukan mewakili nilai tidak null, false sebaliknya

## System::operator!=(const T1\&, const Nullable\<T2\>\&) fungsi


Menentukan apakah nilai yang ditentukan tidak sama dengan nilai yang diwakili oleh objek [Nullable](../nullable/) dengan menerapkan [operator!=()](./) pada nilai-nilai ini.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai pembanding pertama |
| T2 | Tipe dasar dari objek [Nullable](../nullable/) yang mewakili nilai pembanding kedua |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| some | const T1\& | Referensi konstan ke nilai yang akan digunakan sebagai pembanding pertama |
| other | const [Nullable](../nullable/)\<T2\>\& | Referensi konstan ke objek [Nullable](../nullable/) yang nilai yang diwakilinya akan digunakan sebagai pembanding kedua |

### Nilai Kembalian

True jika pembanding tidak sama, otherwise - false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) fungsi


Tidak sama membandingkan dua smart pointer.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe objek yang ditunjuk oleh pointer pertama. |
| Y | Tipe objek yang ditunjuk oleh pointer kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Pointer pertama untuk dibandingkan. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Pointer kedua untuk dibandingkan. |

### Nilai Kembalian

False jika pointer cocok, true sebaliknya.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) fungsi


Memeriksa apakah smart pointer tidak null.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe objek yang ditunjuk oleh pointer. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Pointer yang akan diperiksa. |

### Nilai Kembalian

False jika pointer null, true sebaliknya.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) fungsi


Memeriksa apakah smart pointer tidak null.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe objek yang ditunjuk oleh pointer. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | std::nullptr_t | Pointer yang akan diperiksa. |

### Nilai Kembalian

False jika pointer null, true sebaliknya.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) fungsi


Perbandingan tidak sama antara smart pointer dengan pointer sederhana (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe smart pointer. |
| Y | Tipe pointer sederhana. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pointer untuk dibandingkan (kiri). |
| y | const Y * | pointer untuk dibandingkan (kanan). |

### Nilai Kembalian

False jika pointer cocok, true sebaliknya.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) fungsi


Perbandingan kesetaraan smart pointer dengan pointer sederhana (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe pointer sederhana. |
| Y | Tipe smart pointer. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const X * | pointer untuk dibandingkan (kanan). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pointer untuk dibandingkan (kiri). |

### Nilai Kembalian

False jika pointer cocok, true sebaliknya.

## System::operator!=(Chars\&, const String\&) fungsi


[String](../string/) perbandingan.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| Chars | tipe literal [String](../string/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | Chars\& | literal [String](../string/) untuk dibandingkan. |
| right | const [String](../string/)\& | [String](../string/) untuk dibandingkan. |

### Nilai Kembalian

false jika string cocok, true sebaliknya.

## System::operator!=(T\&, const String\&) fungsi


[String](../string/) perbandingan.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T | tipe pointer [String](../string/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | T\& | pointer [String](../string/) untuk dibandingkan. |
| right | const [String](../string/)\& | [String](../string/) untuk dibandingkan. |

### Nilai Kembalian

false jika string cocok, true sebaliknya.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) fungsi


[Object](../object/) dan perbandingan string.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) untuk dikonversi ke string dan dibandingkan. |
| right | const [String](../string/)\& | [String](../string/) untuk dibandingkan. |

### Nilai Kembalian

false jika representasi string objek sama dengan string, true sebaliknya.

## System::operator!=(std::nullptr_t, const String\&) fungsi


Memeriksa apakah string null.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) yang akan diperiksa. |

### Nilai Kembalian

false jika string null, true sebaliknya.

## System::operator!=(std::nullptr_t, TimeSpan) fungsi




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) fungsi


Menentukan apakah URI yang diwakili oleh objek saat ini dan objek yang ditentukan tidak sama.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Objek [Uri](../uri/) pertama untuk dibandingkan |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Objek [Uri](../uri/) kedua untuk dibandingkan |

### Nilai Kembalian

True jika URI tidak sama, otherwise - false

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Kelas [ArraySegment](../arraysegment/)
* Kelas [DateTime](../datetime/)
* Kelas [DateTimeOffset](../datetimeoffset/)
* Kelas [Nullable](../nullable/)
* Kelas [SmartPtr](../smartptr/)
* Kelas [Object](../object/)
* Kelas [String](../string/)
* Kelas [TimeSpan](../timespan/)
* Kelas [Uri](../uri/)
* Struktur [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)