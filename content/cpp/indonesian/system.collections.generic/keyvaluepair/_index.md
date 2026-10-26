---
title: KeyValuePair
second_title: Aspose.Slides untuk Referensi API C++
description: "Pasangan kunci dan nilai. Tipe ini harus dialokasikan di stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 378
url: /id/system.collections.generic/keyvaluepair/
---
## KeyValuePair kelas

Pasangan kunci dan nilai. Tipe ini harus dialokasikan di stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../../system/smartptr/) untuk mengelola objek tipe ini.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Mendapatkan kunci. |
| const TValue\& [get_Value](./get_value/)() const | Mendapatkan nilai. |
| int [GetHashCode](./gethashcode/)() const | Menghitung hash pasangan kunci-nilai dengan melakukan XOR pada hash kunci dan nilai. |
| **bool** [IsNull](./isnull/)() const | Selalu mengembalikan false. |
| [KeyValuePair](./keyvaluepair/)() | Inisialisasi pasangan kunci-nilai null. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Konstruktor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Konstruktor konversi tipe. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Patch untuk kelas yang mewarisi dari IComparer<KeyValuePair<TKey, TValue>>, tidak membandingkan apa pun. |
| [String](../../system/string/) [ToString](./tostring/)() const | Mengonversi pasangan kunci-nilai menjadi string. |

## Lihat Juga

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)