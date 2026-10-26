---
title: StartsWith()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah string dimulai dengan substring yang ditentukan.
type: docs
weight: 469
url: /id/system/string/startswith/
---
## String::StartsWith(const String\&) const metode

Memeriksa apakah string dimulai dengan substring yang ditentukan.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../)\& | String pencarian. |

### Nilai Kembali

true jika string dimulai dengan substring yang ditentukan, false sebaliknya.

## String::StartsWith(const String\&, System::StringComparison) const metode

Memeriksa apakah string dimulai dengan substring yang ditentukan.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../)\& | String pencarian. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode, lihat [System::StringComparison](../../stringcomparison/) untuk detail. |

### Nilai Kembali

true jika string dimulai dengan substring yang ditentukan, false sebaliknya.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metode

Memeriksa apakah string dimulai dengan substring yang ditentukan.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../)\& | String pencarian. |
| ignoreCase | **bool** | Menentukan apakah perbandingan bersifat tidak sensitif huruf. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Budaya yang digunakan saat melakukan perbandingan string. |

### Nilai Kembali

true jika string dimulai dengan substring yang ditentukan, false sebaliknya.

## Lihat Juga

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)