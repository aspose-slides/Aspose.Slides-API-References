---
title: PrintToStringImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mencetak subclass System::Object menjadi string menggunakan metode ToString()."
type: docs
weight: 14
url: /id/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) fungsi


Mencetak subclass [System::Object](../../system/object/) menjadi string menggunakan metode ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe kelas akhir. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Penunjuk ke objek yang akan dicetak. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

[String](../../system/string/) representasi objek yang diberikan atau "nullptr", jika **value** null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) fungsi


Mencetak subclass [System::Object](../../system/object/) menjadi string menggunakan metode ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe kelas akhir. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Penunjuk ke objek yang akan dicetak. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

[String](../../system/string/) representasi objek yang diberikan atau "nullptr", jika **value** null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fungsi


Mencetak objek menjadi string menggunakan metode ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) untuk dicetak. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

[String](../../system/string/) representasi objek yang diberikan.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fungsi


Mencetak objek menjadi string menggunakan metode PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) untuk dicetak. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

[String](../../system/string/) representasi objek yang diberikan.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fungsi


Mencetak objek menjadi string menggunakan metode PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) untuk dicetak. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

[String](../../system/string/) representasi objek yang diberikan.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) fungsi


Mencetak pasangan menjadi string.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Argumen tipe pasangan pertama. |
| T2 | Argumen tipe pasangan kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) untuk dicetak. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

Representasi string gabungan dari kedua komponen pasangan pertama dan kedua.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) fungsi


Mencetak pasangan menjadi string.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Argumen tipe pasangan pertama. |
| T2 | Argumen tipe pasangan kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) untuk dicetak. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

Representasi string gabungan dari kedua komponen pasangan pertama dan kedua.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fungsi


Mencetak kontainer gaya STL menjadi string dengan mencetak elemennya (tidak lebih dari 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) untuk dicetak. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

Representasi string gabungan dari elemen yang terkandung.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) fungsi


Mencetak tipe lain menjadi string dengan menggunakan fungsi yang disediakan gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) untuk dicetak. |
| s | int | Parameter layanan yang berfungsi sebagai pemilih overload fungsi berdasarkan tipe parameter ini; nilai parameter diabaikan |

### Nilai Kembali

[String](../../system/string/) representasi objek yang diberikan.

## Lihat Juga

* Typedef [SharedPtr](../../system/sharedptr/)
* Kelas [WeakPtr](../../system/weakptr/)
* Kelas [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Kelas [Object](../../system/object/)
* Struktur [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struktur [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struktur [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Pustaka [Aspose.Slides](../../)