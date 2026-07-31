---
title: Concat()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggabungkan array string.
type: docs
weight: 1
url: /id/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) fungsi


Menggabungkan array string.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) dari string untuk digabungkan. |

### Nilai Kembalian

String gabungan.

## System::StringExtra::Concat(const String\&, const String\&) fungsi


Menggabungkan string.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | String pertama untuk digabungkan. |
| str1 | const [String](../../system/string/)\& | String kedua untuk digabungkan. |

### Nilai Kembalian

String parameter yang digabungkan.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) fungsi


Menggabungkan string.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | String pertama untuk digabungkan. |
| str1 | const [String](../../system/string/)\& | String kedua untuk digabungkan. |
| str2 | const [String](../../system/string/)\& | String ketiga untuk digabungkan. |

### Nilai Kembalian

String parameter yang digabungkan.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) fungsi


Menggabungkan string.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | String pertama untuk digabungkan. |
| str1 | const [String](../../system/string/)\& | String kedua untuk digabungkan. |
| str2 | const [String](../../system/string/)\& | String ketiga untuk digabungkan. |
| str3 | const [String](../../system/string/)\& | String keempat untuk digabungkan. |

### Nilai Kembalian

String parameter yang digabungkan.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) fungsi


Mengonversi beberapa objek menjadi string dan menggabungkan string yang dihasilkan. Spesialisasi untuk tipe [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) untuk dikonversi dan digabungkan. |

### Nilai Kembalian

[String](../../system/string/) nilai gabungan dari representasi string semua objek yang diberikan.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) fungsi


Mengonversi beberapa objek menjadi string dan menggabungkan string yang dihasilkan. Spesialisasi untuk tipe aritmetika.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) untuk dikonversi dan digabungkan. |

### Nilai Kembalian

[String](../../system/string/) nilai gabungan dari representasi string semua objek yang diberikan.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) fungsi


Mengonversi beberapa objek menjadi string dan menggabungkan string yang dihasilkan. Spesialisasi untuk struktur dan tipe nilai lainnya.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) untuk dikonversi dan digabungkan. |

### Nilai Kembalian

[String](../../system/string/) nilai gabungan dari representasi string semua objek yang diberikan.

## Lihat Juga

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Library [Aspose.Slides](../../)