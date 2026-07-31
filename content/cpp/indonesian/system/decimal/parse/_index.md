---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi representasi string dari angka desimal menjadi instance yang setara dari kelas Decimal.
type: docs
weight: 469
url: /id/system/decimal/parse/
---
## Decimal::Parse(const String\&) metode

Mengonversi representasi string dari angka desimal menjadi instance yang setara dari kelas [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari sebuah angka |

### Nilai Kembalian

Instance baru dari kelas [Decimal](../) yang mewakili nilai yang setara dengan nilai yang direpresentasikan oleh string yang ditentukan.

## Decimal::Parse(const String\&, Globalization::NumberStyles) metode

Mengonversi representasi string dari angka desimal menjadi instance yang setara dari kelas [Decimal](../) menggunakan gaya yang ditentukan.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai desimal yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enumerasi yang menyediakan informasi tambahan tentang **s**, tentang elemen gaya yang mungkin ada dalam **s**, atau tentang konversi dari **s** ke objek [Decimal](../) |

### Nilai Kembalian

Instance baru dari kelas [Decimal](../) yang mewakili nilai yang setara dengan nilai yang direpresentasikan oleh string yang ditentukan

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi representasi string dari angka desimal menjadi instance yang setara dari kelas [Decimal](../) menggunakan penyedia format yang ditentukan.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai desimal yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format |

### Nilai Kembalian

Instance baru dari kelas [Decimal](../) yang mewakili nilai yang setara dengan nilai yang direpresentasikan oleh string yang ditentukan

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi representasi string dari angka desimal menjadi instance yang setara dari kelas [Decimal](../) menggunakan gaya dan penyedia format yang ditentukan.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai desimal yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enumerasi yang menyediakan informasi tambahan tentang **s**, tentang elemen gaya yang mungkin ada dalam **s**, atau tentang konversi dari **s** ke objek [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format |

### Nilai Kembalian

Instance baru dari kelas [Decimal](../) yang mewakili nilai yang setara dengan nilai yang direpresentasikan oleh string yang ditentukan

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Decimal](../)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)