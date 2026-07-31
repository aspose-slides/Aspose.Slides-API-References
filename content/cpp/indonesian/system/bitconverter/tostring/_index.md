---
title: ToString()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi semua nilai dari array byte yang ditentukan menjadi representasi string heksadesimal. Bentuk huruf yang digunakan dalam notasi heksadesimal dan pemisah yang disisipkan antara setiap pasangan byte yang bersebelahan ditentukan melalui argumen yang bersangkutan.
type: docs
weight: 157
url: /id/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) method

Mengonversi semua nilai dari array byte yang ditentukan menjadi representasi string heksadesimal. Bentuk huruf yang digunakan dalam notasi heksadesimal dan pemisah yang disisipkan antara setiap pasangan byte yang bersebelahan ditentukan melalui argumen yang bersangkutan.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| uppercase | **bool** | Specifies the case of letters to use in resulting hexadecimal representation |
| separator | const [String](../../string/)\& | A string used as a separator inserted between each pair of neighbouring bytes in the resulting string |

### Nilai Kembali

[String](../../string/) containing hexadecimal representation of the specified byte array

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) method

Mengonversi nilai-nilai dari array byte yang ditentukan menjadi representasi string heksadesimal mulai dari indeks yang ditentukan.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | [Index](../../index/) in the specified array at which to start converting |

### Nilai Kembali

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) method

Mengonversi rentang nilai dari array byte yang ditentukan menjadi representasi string heksadesimal.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | [Index](../../index/) in the specified array at which the range of the byte array elements to convert begins |
| length | int | Panjang rentang elemen array byte yang akan dikonversi |

### Nilai Kembali

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [String](../../string/)
* Kelas [BitConverter](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)