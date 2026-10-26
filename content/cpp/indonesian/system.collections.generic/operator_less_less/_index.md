---
title: operator<<()
second_title: Referensi API Aspose.Slides untuk C++
description: Masukkan data ke dalam stream menggunakan enkoding UTF-8.
type: docs
weight: 716
url: /id/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) fungsi

Masukkan data ke dalam stream menggunakan enkoding UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | Tipe kunci. |
| TValue | Tipe nilai. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | std::ostream\& | Stream output untuk memasukkan data. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) untuk dimasukkan. |

### Nilai Kembalian

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) fungsi

Masukkan data ke dalam stream.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | Tipe kunci. |
| TValue | Tipe nilai. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | std::wostream\& | Stream output untuk memasukkan data. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) untuk dimasukkan. |

### Nilai Kembalian

**stream**.

## Lihat Juga

* Kelas [KeyValuePair](../keyvaluepair/)
* Ruang Nama [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)