---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka ke nilai Decimal yang setara.
type: docs
weight: 482
url: /id/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka ke nilai [Decimal](../) yang setara.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| result | [Decimal](../)\& | Referensi ke variabel [Decimal](../) tempat hasil konversi disimpan |

### Nilai Kembalian

True jika konversi berhasil, jika tidak - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka ke nilai [Decimal](../) yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string sebuah angka |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string |
| result | [Decimal](../)\& | Argumen output; berisi hasil konversi |

### Nilai Kembalian

True jika konversi berhasil, jika tidak - false

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)