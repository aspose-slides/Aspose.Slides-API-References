---
title: Round()
second_title: Referensi API Aspose.Slides untuk C++
description: Membulatkan nilai yang ditentukan ke nilai bulat terdekat.
type: docs
weight: 157
url: /id/system/mathf/round/
---
## MathF::Round(float) metode

Membulatkan nilai yang ditentukan ke nilai bulat terdekat.

```cpp
static float System::MathF::Round(float a)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | **float** | Nilai yang akan dibulatkan |

### Nilai Kembalian

**a** dibulatkan ke nilai bulat terdekat

## MathF::Round(float, int) metode

Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan.

```cpp
static float System::MathF::Round(float value, int digits)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **float** | Nilai yang akan dibulatkan |
| digits | int | Jumlah digit pecahan dalam nilai yang dibulatkan |

### Nilai Kembalian

Angka dengan jumlah digit yang ditentukan terdekat dengan **value**

## MathF::Round(float, MidpointRounding) metode

Membulatkan nilai yang ditentukan ke bilangan bulat terdekat. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama dekatnya dengan dua bilangan terdekat.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **float** | Nilai yang akan dibulatkan |
| mode | [MidpointRounding](../../midpointrounding/) | Menentukan cara melakukan pembulatan jika **value** sama dekatnya dengan dua bilangan terdekat. |

### Nilai Kembalian

**value** dibulatkan ke bilangan bulat terdekat

## MathF::Round(float, int, MidpointRounding) metode

Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama dekatnya dengan dua bilangan terdekat.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **float** | Nilai yang akan dibulatkan |
| digits | int | Jumlah digit pecahan dalam nilai yang dibulatkan |
| mode | [MidpointRounding](../../midpointrounding/) | Menentukan cara melakukan pembulatan jika **value** sama dekatnya dengan dua bilangan terdekat. |

### Nilai Kembalian

Angka dengan jumlah digit yang ditentukan terdekat dengan **value**

## Lihat Juga

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)