---
title: EndsWith()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah string diakhiri dengan substring yang ditentukan.
type: docs
weight: 482
url: /id/system/string/endswith/
---
## String::EndsWith(const String\&) const metode

Memeriksa apakah string diakhiri dengan substring yang ditentukan.

```cpp
bool System::String::EndsWith(const String &value) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../)\& | String pencarian. |

### Nilai Kembalian

true jika string diakhiri dengan substring yang ditentukan, false jika tidak.

## String::EndsWith(const String\&, System::StringComparison) const metode

Memeriksa apakah string diakhiri dengan substring yang ditentukan.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../)\& | String pencarian. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode, lihat [System::StringComparison](../../stringcomparison/) untuk detail. |

### Nilai Kembalian

true jika string diakhiri dengan substring yang ditentukan, false jika tidak.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metode

Memeriksa apakah string diakhiri dengan substring yang ditentukan.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../)\& | String pencarian. |
| ignoreCase | **bool** | Menentukan apakah perbandingan tidak sensitif huruf. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Budaya yang digunakan saat melakukan perbandingan string. |

### Nilai Kembalian

true jika string diakhiri dengan substring yang ditentukan, false jika tidak.

## Lihat Juga

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)