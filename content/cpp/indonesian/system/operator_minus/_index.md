---
title: operator-()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung jumlah hari antara dua hari dalam seminggu.
type: docs
weight: 2172
url: /id/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) fungsi

Menghitung jumlah hari antara dua hari dalam seminggu.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | The minuend |
| b | [DayOfWeek](../dayofweek/) | The subtrahend |

### Nilai Kembali

Jumlah hari antara hari kerja **a** dan **b**; nilai kembali adalah angka negatif jika *berlaku* setelah ****

## System::operator-(const T\&, const Decimal\&) fungsi

Mengembalikan instance baru dari kelas [Decimal](../decimal/) yang mewakili nilai yang merupakan hasil pengurangan nilai yang direpresentasikan oleh objek [Decimal](../decimal/) yang ditentukan dari nilai yang ditentukan.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const T\& | Nilai yang akan dikurangkan |
| d | const [Decimal](../decimal/)\& | Objek [Decimal](../decimal/) yang merepresentasikan nilai yang dikurangkan |

### Nilai Kembali

Instance baru dari kelas [Decimal](../decimal/) yang mewakili nilai yang merupakan hasil pengurangan nilai yang direpresentasikan oleh **d** dari **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) fungsi

Memutuskan semua callback pada delegate tangan kanan dari akhir daftar callback delegate tangan kiri.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegate yang callback-nya akan dihapus. |
| rhv | MulticastDelegate\<T\> | Delegate yang callback-nya akan dihapus. |

### Nilai Kembali

Mengembalikan delegate yang berisi callback dari nilai tangan kiri, tetapi tanpa callback dari nilai tangan kanan.

## System::operator-(const T1\&, const Nullable\<T2\>\&) fungsi

Mengurangi nilai yang tidak dapat bernilai null dan nilai yang dapat bernilai null.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe operand kiri. |
| T2 | Tipe operand kanan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| some | const T1\& | Operand kiri. |
| other | const [Nullable](../nullable/)\<T2\>\& | Operand kanan. |

### Nilai Kembali

Hasil pengurangan.

## Lihat Juga

* Enum [DayOfWeek](../dayofweek/)
* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)