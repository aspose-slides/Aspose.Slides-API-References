---
title: HexUnescape()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi representasi heksadesimal yang ditentukan dari sebuah karakter menjadi karakter.
type: docs
weight: 443
url: /id/system/uri/hexunescape/
---
## Uri::HexUnescape(const String&, int32_t&) metode


Mengonversi representasi heksadesimal yang ditentukan dari sebuah karakter menjadi karakter.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pattern | const [String](../../string/)& | Sebuah string yang berisi representasi heksadesimal dari sebuah karakter |
| index | **int32_t**& | Posisi dalam **pattern** dimana representasi heksadesimal dari sebuah karakter dimulai |

### Nilai Kembali

Karakter yang direpresentasikan oleh pengkodean heksadesimal pada posisi **index**. Jika karakter pada **index** tidak dienkode secara heksadesimal, karakter pada **index** dikembalikan. Nilai **index** dinaikkan untuk menunjuk ke karakter setelah yang dikembalikan.

## Lihat Juga

* Kelas [String](../../string/)
* Kelas [Uri](../)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)