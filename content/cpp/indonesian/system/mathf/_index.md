---
title: MathF
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi fungsi matematika untuk nilai floating-point presisi tunggal. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh pernah membuat instance darinya dengan cara apa pun.
type: docs
weight: 1795
url: /id/system/mathf/
---
## MathF struct

Berisi fungsi matematika untuk nilai floating-point presisi tunggal. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh pernah membuat instance darinya dengan cara apa pun.

```cpp
class MathF
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static T [Abs](./abs/)(T) | Mengembalikan nilai absolut dari nilai yang ditentukan. |
| static **float** [Acos](./acos/)(**float**) | Menghitung arccosine dari nilai yang ditentukan. |
| static **float** [Asin](./asin/)(**float**) | Menghitung arcsin dari nilai yang ditentukan. |
| static **float** [Atan](./atan/)(**float**) | Menghitung arctan dari nilai yang ditentukan. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Menghitung arctan dari rasio nilai yang ditentukan. |
| static **float** [Ceiling](./ceiling/)(**float**) | Mengembalikan nilai bulat terkecil yang lebih besar atau sama dengan nilai yang ditentukan. |
| static **float** [Cos](./cos/)(**float**) | Menghitung kosinus dari nilai yang ditentukan. |
| static **float** [Cosh](./cosh/)(**float**) | Menghitung kosinus hiperbolik dari nilai yang ditentukan. |
| static **float** [Exp](./exp/)(**float**) | Mengembalikan konstanta e dipangkatkan dengan pangkat yang ditentukan. |
| static **float** [Floor](./floor/)(**float**) | Mengembalikan nilai bulat terbesar yang lebih kecil atau sama dengan nilai yang ditentukan. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Mengembalikan sisa hasil bagi dari pembagian satu angka yang ditentukan dengan angka lain yang ditentukan. |
| static **float** [Log](./log/)(**float**) | Mengembalikan logaritma natural dari nilai yang ditentukan. |
| static **float** [Log](./log/)(**float**, **float**) | Mengembalikan logaritma dari nilai yang ditentukan dengan basis yang ditentukan. |
| static **float** [Log10](./log10/)(**float**) | Mengembalikan logaritma basis-10 dari nilai yang ditentukan. |
| static **float** [Pow](./pow/)(**float**, **float**) | Mengembalikan nilai yang ditentukan dipangkatkan dengan pangkat yang ditentukan. |
| static **float** [Round](./round/)(**float**) | Membulatkan nilai yang ditentukan ke nilai bulat terdekat. |
| static **float** [Round](./round/)(**float**, int) | Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke angka bulat terdekat. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama jauh dengan dua angka terdekat. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama jauh dengan dua angka terdekat. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama jauh dengan dua angka terdekat. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Menentukan tanda dari nilai bulat bertanda yang ditentukan. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Menentukan tanda dari nilai floating-point yang ditentukan. |
| static **float** [Sin](./sin/)(**float**) | Menghitung sinus dari nilai yang ditentukan. |
| static **float** [Sinh](./sinh/)(**float**) | Menghitung sinus hiperbolik dari nilai yang ditentukan. |
| static **float** [Sqrt](./sqrt/)(**float**) | Mengembalikan akar kuadrat dari nilai yang ditentukan. |
| static **float** [Tan](./tan/)(**float**) | Menghitung tangen dari nilai yang ditentukan. |
| static **float** [Tanh](./tanh/)(**float**) | Menghitung tangen hiperbolik dari nilai yang ditentukan. |
| static **float** [Truncate](./truncate/)(**float**) | Mengembalikan nilai floating point presisi float yang bagian integralnya sama dengan nilai yang ditentukan dengan semua digit pecahan dibuang. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [E](./e/) | Basis logaritma natural. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | Konstanta bilangan Pi. |
| static [Tau](./tau/) | Nilai Tau. |

## Lihat Juga

* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)