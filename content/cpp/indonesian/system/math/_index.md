---
title: Math
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi fungsi matematika. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh membuat instance darinya dengan cara apa pun.
type: docs
weight: 1782
url: /id/system/math/
---
## Math struct

Berisi fungsi matematika. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh membuat instance darinya dengan cara apa pun.

```cpp
class Math
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static T [Abs](./abs/)(T) | Mengembalikan nilai mutlak dari nilai yang ditentukan. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Mengembalikan nilai mutlak dari nilai yang direpresentasikan oleh objek [Decimal](../decimal/) yang ditentukan. |
| static **double** [Acos](./acos/)(**double**) | Menghitung arc cosinus dari nilai yang ditentukan. |
| static **double** [Asin](./asin/)(**double**) | Menghitung arc sinus dari nilai yang ditentukan. |
| static **double** [Atan](./atan/)(**double**) | Menghitung arc tangen dari nilai yang ditentukan. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Menghitung arc tangen dari rasio nilai yang ditentukan. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Mengembalikan hasil perkalian penuh dari dua bilangan bulat 32-bit. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Mengembalikan nilai integral terkecil yang lebih besar dari atau sama dengan nilai yang ditentukan. |
| static **double** [Ceiling](./ceiling/)(**double**) | Mengembalikan nilai integral terkecil yang lebih besar dari atau sama dengan nilai yang ditentukan. |
| static **double** [Cos](./cos/)(**double**) | Menghitung kosinus dari nilai yang ditentukan. |
| static **double** [Cosh](./cosh/)(**double**) | Menghitung kosinus hiperbolik dari nilai yang ditentukan. |
| static int [DivRem](./divrem/)(int, int, int\&) | Menghitung hasil bagi dari dua bilangan bulat 32-bit dan sisanya. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Menghitung hasil bagi dari dua bilangan bulat 64-bit dan sisanya. |
| static **double** [Exp](./exp/)(**double**) | Mengembalikan konstanta e dipangkatkan dengan pangkat yang ditentukan. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Mengembalikan nilai integral terbesar yang lebih kecil dari atau sama dengan nilai yang ditentukan. |
| static **double** [Floor](./floor/)(**double**) | Mengembalikan nilai integral terbesar yang lebih kecil dari atau sama dengan nilai yang ditentukan. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Mengembalikan sisa hasil pembagian dari suatu angka yang ditentukan dengan angka lain yang ditentukan. |
| static **double** [Log](./log/)(**double**) | Mengembalikan logaritma natural dari nilai yang ditentukan. |
| static **double** [Log](./log/)(**double**, **double**) | Mengembalikan logaritma dari nilai yang ditentukan dalam basis yang ditentukan. |
| static **double** [Log10](./log10/)(**double**) | Mengembalikan logaritma basis-10 dari nilai yang ditentukan. |
| static auto [Max](./max/)(T0, T1) | Mengembalikan nilai terbesar dari dua nilai numerik yang ditentukan. |
| static T0 [Max](./max/)(T0, T1) | Mengembalikan nilai terbesar dari dua nilai numerik yang ditentukan. |
| **float** [Max_](./max_/)(**float**, **float**) | Mengembalikan nilai floating point presisi tunggal terbesar dari dua nilai yang ditentukan. |
| **double** [Max_](./max_/)(**double**, **double**) | Mengembalikan nilai floating point presisi ganda terbesar dari dua nilai yang ditentukan. |
| static auto [Min](./min/)(T0, T1) | Mengembalikan nilai terkecil dari dua nilai numerik yang ditentukan. |
| static T0 [Min](./min/)(T0, T1) | Mengembalikan nilai terkecil dari dua nilai numerik yang ditentukan. |
| **float** [Min_](./min_/)(**float**, **float**) | Mengembalikan nilai floating point presisi tunggal terkecil dari dua nilai yang ditentukan. |
| **double** [Min_](./min_/)(**double**, **double**) | Mengembalikan nilai floating point presisi ganda terkecil dari dua nilai yang ditentukan. |
| static T [Modulus](./modulus/)(T, T) | Menghitung sisa hasil pembagian satu nilai yang ditentukan dengan nilai lain yang ditentukan. |
| static **double** [Pow](./pow/)(**double**, **double**) | Mengembalikan nilai yang ditentukan dipangkatkan dengan pangkat yang ditentukan. |
| static **double** [Round](./round/)(**double**) | Membulatkan nilai yang ditentukan ke nilai integral terdekat. |
| static **double** [Round](./round/)(**double**, int) | Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke bilangan integral terdekat. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama dekatnya dengan dua bilangan terdekat. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama dekatnya dengan dua bilangan terdekat. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Membulatkan nilai yang ditentukan ke nilai integral terdekat. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke bilangan integral terdekat. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama dekatnya dengan dua bilangan terdekat. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama dekatnya dengan dua bilangan terdekat. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Menentukan tanda dari nilai integral bertanda yang ditentukan. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Menentukan tanda dari nilai floating-point yang ditentukan. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Menentukan tanda dari nilai desimal yang ditentukan. |
| static **double** [Sin](./sin/)(**double**) | Menghitung sinus dari nilai yang ditentukan. |
| static **double** [Sinh](./sinh/)(**double**) | Menghitung sinus hiperbolik dari nilai yang ditentukan. |
| static **double** [Sqrt](./sqrt/)(**double**) | Mengembalikan akar kuadrat dari nilai yang ditentukan. |
| static **double** [Tan](./tan/)(**double**) | Menghitung tangen dari nilai yang ditentukan. |
| static **double** [Tanh](./tanh/)(**double**) | Menghitung tangen hiperbolik dari nilai yang ditentukan. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Mengembalikan objek [Decimal](../decimal/) yang merepresentasikan nilai yang bagian integralnya sama dengan nilai yang direpresentasikan oleh objek [Decimal](../decimal/) yang ditentukan dengan semua digit pecahan dibuang. |
| static **double** [Truncate](./truncate/)(**double**) | Mengembalikan nilai floating point presisi ganda yang memiliki bagian integral yang sama dengan nilai yang ditentukan dengan semua digit pecahan dibuang. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [E](./e/) | Basis logaritma natural. |
| static [NaN](./nan/) | Merepresentasikan nilai bukan angka. |
| static [NegativeInfinity](./negativeinfinity/) | Merepresentasikan tak terhingga negatif. |
| static [PI](./pi/) | Konstanta bilangan Pi. |
| static [PositiveInfinity](./positiveinfinity/) | Merepresentasikan tak terhingga positif. |

## Catatan

```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Menampilkan nilai absolut.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Menampilkan sinus PI/2 dan kosinus PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)