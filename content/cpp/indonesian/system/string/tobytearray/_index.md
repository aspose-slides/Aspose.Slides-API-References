---
title: ToByteArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string atau substring menjadi array byte.
type: docs
weight: 508
url: /id/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const metode

Mengonversi string atau substring menjadi array byte.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks awal substring. |
| length | **int32_t** | Panjang substring. |
| LE | **bool** | Jika true, enkode karakter menggunakan endianness kecil; bila tidak, gunakan endianness besar. |

### Nilai Kembalian

[Array](../../array/) yang berisi byte yang mewakili karakter string.

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [String](../)
* Namespace [System](../../)
* Pustaka [Aspose.Slides](../../../)