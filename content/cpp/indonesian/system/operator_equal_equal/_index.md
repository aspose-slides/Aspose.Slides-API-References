---
title: operator==()
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 2042
url: /id/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) fungsi




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) fungsi




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) fungsi




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) fungsi


Menentukan apakah objek [Nullable](../nullable/) yang ditentukan mewakili nilai yang sama dengan null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | std::nullptr_t | Referensi konstan ke objek [Nullable](../nullable/) untuk diuji |

### Nilai Kembalian

True jika objek yang ditentukan mewakili nilai null, false sebaliknya

## System::operator==(const T1\&, const Nullable\<T2\>\&) fungsi


Menentukan apakah nilai yang ditentukan sama dengan nilai yang diwakili oleh objek [Nullable](../nullable/) yang ditentukan dengan menerapkan [operator==()](./) pada nilai-nilai tersebut.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai perbandingan pertama |
| T2 | Tipe dasar dari objek [Nullable](../nullable/) yang mewakili nilai perbandingan kedua |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| some | const T1\& | Referensi konstan ke nilai yang akan digunakan sebagai perbandingan pertama |
| other | const [Nullable](../nullable/)\<T2\>\& | Referensi konstan ke objek [Nullable](../nullable/) yang nilai yang diwakilinya akan digunakan sebagai perbandingan kedua |

### Nilai Kembalian

True jika perbandingan sama, otherwise - false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) fungsi


Membandingkan dua smart pointer secara setara.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe yang ditunjuk oleh pointer pertama. |
| Y | Tipe yang ditunjuk oleh pointer kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Pointer pertama untuk dibandingkan. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Pointer kedua untuk dibandingkan. |

### Nilai Kembalian

True jika pointer cocok, false sebaliknya.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) fungsi


Memeriksa apakah smart pointer bernilai null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe yang ditunjuk oleh pointer. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | std::nullptr_t | Pointer yang akan diperiksa. |

### Nilai Kembalian

True jika pointer null, false sebaliknya.

## System::operator==(const SmartPtr\<X\>\&, const Y *) fungsi


Perbandingan kesetaraan smart pointer dengan pointer sederhana (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| X | tipe smart pointer. |
| Y | tipe pointer sederhana. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pointer untuk dibandingkan (kiri). |
| y | const Y * | pointer untuk dibandingkan (kanan). |

### Nilai Kembalian

True jika pointer cocok, false sebaliknya.

## System::operator==(const X *, const SmartPtr\<Y\>\&) fungsi


Perbandingan kesetaraan smart pointer dengan pointer sederhana (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| X | tipe pointer sederhana. |
| Y | tipe smart pointer. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const X * | pointer untuk dibandingkan (kanan). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pointer untuk dibandingkan (kiri). |

### Nilai Kembalian

True jika pointer cocok, false sebaliknya.

## System::operator==(T const\&, std::nullptr_t) fungsi


Memeriksa apakah objek tipe nilai (struktur C# yang diterjemahkan, dll.) bernilai null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | T const\& | [Object](../object/) yang akan diperiksa. |

### Nilai Kembalian

True jika objek null, false sebaliknya.

## System::operator==(std::nullptr_t, T const\&) fungsi


Memeriksa apakah objek tipe nilai (struktur C# yang diterjemahkan, dll.) bernilai null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) yang akan diperiksa. |

### Nilai Kembalian

True jika objek null, false sebaliknya.

## System::operator==(Chars\&, const String\&) fungsi


[String](../string/) perbandingan.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| Chars | Tipe literal [String](../string/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | Chars\& | Literal [String](../string/) untuk dibandingkan. |
| right | const [String](../string/)\& | [String](../string/) untuk dibandingkan. |

### Nilai Kembalian

true jika string cocok, false sebaliknya.

## System::operator==(T\&, const String\&) fungsi


[String](../string/) perbandingan.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe pointer [String](../string/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | T\& | Pointer [String](../string/) untuk dibandingkan. |
| right | const [String](../string/)\& | [String](../string/) untuk dibandingkan. |

### Nilai Kembalian

true jika string cocok, false sebaliknya.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) fungsi


[Object](../object/) dan perbandingan string.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) untuk dikonversi ke string dan dibandingkan. |
| right | const [String](../string/)\& | [String](../string/) untuk dibandingkan. |

### Nilai Kembalian

true jika representasi string objek sama dengan string, false sebaliknya.

## System::operator==(std::nullptr_t, const String\&) fungsi


Memeriksa apakah string bernilai null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) yang akan diperiksa. |

### Nilai Kembalian

true jika string null, false sebaliknya.

## System::operator==(std::nullptr_t, TimeSpan) fungsi




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) fungsi


Menentukan apakah URI yang diwakili oleh objek saat ini dan objek yang ditentukan sama.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Objek [Uri](../uri/) pertama untuk dibandingkan |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Objek [Uri](../uri/) kedua untuk dibandingkan |

### Nilai Kembalian

True jika URI sama, otherwise - false

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)