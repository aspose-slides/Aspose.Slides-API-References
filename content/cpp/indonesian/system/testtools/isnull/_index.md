---
title: IsNull()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah nilai tertentu bernilai null. Versi untuk tipe aritmetika dan enum.
type: docs
weight: 1
url: /id/system/testtools/isnull/
---
## TestTools::IsNull(T) metode

Memeriksa apakah nilai tertentu bernilai null. [Version](../../version/) untuk tipe aritmetika dan enum.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai yang diperiksa. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T | Nilai yang akan diperiksa apakah null. |

### Nilai Kembali

Selalu mengembalikan false.

## TestTools::IsNull(const T&) metode

Memeriksa apakah nilai tertentu bernilai null. [Version](../../version/) untuk tipe nilai non-aritmetika dan non-enum.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai yang diperiksa. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | Nilai yang akan diperiksa apakah null. |

### Nilai Kembali

True jika objek dibandingkan dengan nullptr sebagai true, false sebaliknya.

## TestTools::IsNull(const SharedPtr\<T\>\&) metode

Memeriksa apakah nilai tertentu bernilai null. [Version](../../version/) untuk tipe nilai non-aritmetika.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai yang diperiksa. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Nilai yang akan diperiksa apakah null. |

### Nilai Kembali

True jika objek dibandingkan dengan nullptr sebagai true, false sebaliknya.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) metode

Memeriksa apakah nilai tertentu bernilai null. [Version](../../version/) untuk pasangan kunci-nilai.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| K | Tipe kunci. |
| V | Tipe nilai. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Objek pasangan. |

### Nilai Kembali

True jika pasangan dianggap null, false sebaliknya.

## TestTools::IsNull(const System::String&) metode

Memeriksa apakah string bernilai null.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) untuk diperiksa. |

### Nilai Kembali

True jika string dianggap null, false sebaliknya.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Kelas [String](../../string/)
* Struktur [TestTools](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)