---
title: operator+()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah instance baru dari kelas Decimal yang mewakili nilai yang merupakan hasil penjumlahan nilai yang ditentukan dan nilai yang diwakili oleh objek Decimal yang diberikan.
type: docs
weight: 2185
url: /id/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) fungsi

Mengembalikan sebuah instance baru dari kelas [Decimal](../decimal/) yang mewakili nilai yang merupakan hasil penjumlahan nilai yang ditentukan dan nilai yang diwakili oleh objek [Decimal](../decimal/) yang diberikan.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const T\& | Operand pertama |
| d | const [Decimal](../decimal/)\& | Referensi konstan ke objek [Decimal](../decimal/) yang mewakili operand kedua |

### Nilai Kembali

Sebuah instance baru dari kelas [Decimal](../decimal/) yang mewakili nilai yang merupakan hasil penjumlahan **x** dan nilai yang diwakili oleh **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) fungsi

Menghubungkan semua callback dari delegasi tangan kanan ke akhir daftar callback delegasi tangan kiri.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegasi yang akan ditambahkan callback-nya. |
| rhv | MulticastDelegate\<T\> | Delegasi yang callback-nya sedang ditambahkan. |

### Nilai Kembali

Mengembalikan sebuah delegasi yang berisi callback dari nilai tangan kiri, lalu callback dari tangan kanan.

## System::operator+(const T1\&, const Nullable\<T2\>\&) fungsi

Menjumlahkan nilai yang tidak dapat bernilai null dan nilai yang dapat bernilai null.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### Parameter Template

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

Hasil penjumlahan.

## System::operator+(T\&, const String\&) fungsi

[String](../string/) penggabungan.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T | [String](../string/) tipe literal. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | T\& | Literal untuk digabungkan ke string. |
| right | const [String](../string/)\& | [String](../string/) untuk digabungkan. |

### Nilai Kembali

String yang digabungkan.

## System::operator+(T\&, const String\&) fungsi

[String](../string/) penggabungan.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T | [String](../string/) tipe pointer. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer untuk digabungkan ke string. |
| right | const [String](../string/)\& | [String](../string/) untuk digabungkan. |

### Nilai Kembali

String yang digabungkan.

## System::operator+(const char_t, const String\&) fungsi

[String](../string/) penggabungan.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | const char_t | Karakter untuk digabungkan ke string. |
| right | const [String](../string/)\& | [String](../string/) untuk digabungkan. |

### Nilai Kembali

String yang digabungkan.

## Lihat Juga

* Kelas [Decimal](../decimal/)
* Kelas [Nullable](../nullable/)
* Kelas [String](../string/)
* Struktur [IsStringLiteral](../isstringliteral/)
* Struktur [IsStringPointer](../isstringpointer/)
* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)