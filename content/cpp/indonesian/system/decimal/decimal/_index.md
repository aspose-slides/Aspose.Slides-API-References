---
title: Decimal()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance yang mewakili 0.
type: docs
weight: 1
url: /id/system/decimal/decimal/
---
## Decimal::Decimal() konstruktor

Membuat sebuah instance yang mewakili 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | std::int8_t | nilai integer 8-bit yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(std::int16_t) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | std::int16_t | nilai integer 16-bit yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(std::int32_t) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | std::int32_t | nilai integer 32-bit yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(std::int64_t) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | std::int64_t | nilai integer 64-bit yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(std::uint8_t) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | std::uint8_t | nilai integer tak bertanda 8-bit yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(std::uint16_t) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | std::uint16_t | nilai integer tak bertanda 16-bit yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(std::uint32_t) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | std::uint32_t | nilai integer tak bertanda 32-bit yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(std::uint64_t) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | std::uint64_t | nilai integer tak bertanda 64-bit yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(float) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(float f)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| f | **float** | nilai floating-point presisi tunggal yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(double) konstruktor

Membuat sebuah instance yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(double d)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| d | **double** | nilai floating-point presisi ganda yang akan direpresentasikan oleh objek [Decimal](../) yang sedang dibangun |

## Decimal::Decimal(const std::string\&) konstruktor

Membuat sebuah instance yang mewakili nilai yang representasinya string ditentukan sebagai sebuah instance kelas std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) konstruktor

Membuat sebuah objek [Decimal](../) dari komponen-komponen yang ditentukan.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lo | **int32_t** | 32 bit rendah dari nilai |
| mid | **int32_t** | 32 bit menengah dari nilai |
| hi | **int32_t** | 32 bit tinggi dari nilai |
| isNegative | **bool** | Menentukan apakah nilai bernilai negatif |
| scale | **uint8_t** | Pangkat 10 berkisar antara 0 hingga 28 |

## Decimal::Decimal(const Decimal\&) konstruktor

Membuat sebuah instance kelas [Decimal](../) yang mewakili angka yang sama dengan objek [Decimal](../) yang ditentukan.

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| d | const [Decimal](../)\& | objek [Decimal](../) untuk menyalin nilai darinya |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) konstruktor

Membuat sebuah instance kelas [Decimal](../) dari array integer yang berisi representasi biner.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | array integer yang berisi representasi biner. |

## Decimal::Decimal(std::nullptr_t) konstruktor

Selalu melempar ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) konstruktor

Membuat sebuah instance kelas [Decimal](../) yang mewakili nilai yang ditentukan.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | referensi konstan ke nilai yang akan direpresentasikan oleh objek yang sedang dibangun |

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Kelas [Decimal](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)