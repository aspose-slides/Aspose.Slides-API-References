---
title: Round()
second_title: Referensi API Aspose.Slides untuk C++
description: Membulatkan nilai yang ditentukan ke bilangan bulat terdekat. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan berada pada jarak yang sama dengan dua angka terdekat.
type: docs
weight: 404
url: /id/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) metode

Membulatkan nilai yang ditentukan ke bilangan bulat terdekat. Sebuah parameter menentukan perilaku fungsi jika **nilai** berada pada jarak yang sama dengan dua angka terdekat.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| d | const [Decimal](../)\& | Nilai yang akan dibulatkan |
| mode | [MidpointRounding](../../midpointrounding/) | Menentukan cara melakukan pembulatan jika **nilai** berada pada jarak yang sama dengan dua angka terdekat. |

### Nilai Kembali

**d** dibulatkan ke nilai bulat terdekat

## Decimal::Round(const Decimal\&, int, MidpointRounding) metode

Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. Sebuah parameter menentukan perilaku fungsi jika **nilai** berada pada jarak yang sama dengan dua angka terdekat.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| d | const [Decimal](../)\& | Nilai yang akan dibulatkan |
| digits | int | Jumlah digit pecahan dalam nilai yang dibulatkan |
| mode | [MidpointRounding](../../midpointrounding/) | Menentukan cara melakukan pembulatan jika **nilai** berada pada jarak yang sama dengan dua angka terdekat. |

### Nilai Kembali

Angka dengan jumlah digit yang ditentukan paling dekat dengan **nilai**

## Lihat Juga

* Enum [MidpointRounding](../../midpointrounding/)
* Kelas [Decimal](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)