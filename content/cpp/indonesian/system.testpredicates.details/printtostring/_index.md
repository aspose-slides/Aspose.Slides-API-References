---
title: PrintToString()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencetak objek ke string dengan memilih fungsi serializer yang tepat.
type: docs
weight: 1
url: /id/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T&) fungsi

Mencetak objek ke string dengan memilih fungsi serializer yang tepat.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) untuk dicetak. |

### Nilai Kembali

[String](../../system/string/) representasi dari objek yang diberikan.

## System::TestPredicates::Details::PrintToString(const T&) fungsi

Mencetak kontainer gaya ICollection ke string dengan mencetak elemennya (tidak lebih dari 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) untuk dicetak. |

### Nilai Kembali

Representasi string gabungan dari elemen yang terkandung.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) fungsi

Mencetak nullptr ke string.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Nilai Kembali

"nullptr" string.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) fungsi

Mencetak koleksi [IEnumerable<bool>](../../system.collections.generic/ienumerable/) ke string dengan mencetak elemennya (tidak lebih dari 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) untuk dicetak. |

### Nilai Kembali

Representasi string gabungan dari elemen yang terkandung.

## Lihat Juga

* Kelas [IEnumerable](../../system.collections.generic/ienumerable/)
* Struktur [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Namespace [System::TestPredicates::Details](../)
* Perpustakaan [Aspose.Slides](../../)