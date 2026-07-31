---
title: TestTools
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan sekumpulan metode berguna yang memeriksa beberapa properti dasar dari berbagai tipe dan fungsi.
type: docs
weight: 1925
url: /id/system/testtools/
---
## TestTools struct

Menyediakan sekumpulan metode berguna yang memeriksa beberapa properti dasar dari berbagai tipe dan fungsi.

```cpp
class TestTools
```

## Metode

| Method | Description |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Memeriksa apakah fungsi melemparkan pengecualian dari jenis apa pun. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Memeriksa apakah string kosong. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Memeriksa apakah koleksi kosong. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Memeriksa apakah nilai tertentu null. [Version](../version/) untuk tipe aritmetika dan enum. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Memeriksa apakah nilai tertentu null. [Version](../version/) untuk tipe nilai non-aritmetika dan non-enum. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Memeriksa apakah nilai tertentu null. [Version](../version/) untuk tipe nilai non-aritmetika. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Memeriksa apakah nilai tertentu null. [Version](../version/) untuk pasangan kunci-nilai. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Memeriksa apakah string null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Memeriksa apakah koleksi null atau kosong. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Memeriksa apakah string null atau kosong. |

## Lihat Juga

* Ruang Nama [System](../)
* Library [Aspose.Slides](../../)