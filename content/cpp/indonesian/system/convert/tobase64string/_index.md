---
title: ToBase64String()
second_title: Referensi API Aspose.Slides untuk C++
description: Base-64 mengkodekan elemen dalam byte array yang ditentukan dan mengembalikan data yang telah dikodekan sebagai string.
type: docs
weight: 40
url: /id/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) metode

Base-64 mengkodekan elemen dalam byte array yang ditentukan dan mengembalikan data yang telah dikodekan sebagai string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Array byte yang akan dikodekan |
| insert_line_breaks | **bool** | Menentukan apakah karakter pemutus baris harus dimasukkan ke dalam string output setelah setiap 76 karakter base-64 |

### Nilai Kembali

String yang berisi representasi base-64 yang telah dikodekan dari array input

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) metode

Base-64 mengkodekan rentang elemen dalam byte array yang ditentukan dan mengembalikan data yang telah dikodekan sebagai string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Array byte yang berisi rentang elemen yang akan dikodekan |
| offset_in | int | Indeks elemen dalam array input dimana rentang yang akan dikodekan dimulai |
| length | int | Panjang rentang elemen yang akan dikodekan |
| insert_line_breaks | **bool** | Menentukan apakah karakter pemutus baris harus dimasukkan ke dalam string output setelah setiap 76 karakter base-64 |

### Nilai Kembali

String yang berisi representasi base-64 yang telah dikodekan dari rentang elemen array input

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) metode

Base-64 mengkodekan elemen dalam byte array yang ditentukan dan mengembalikan data yang telah dikodekan sebagai string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Array byte yang akan dikodekan |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Menentukan opsi pemformatan data yang dikodekan base-64 |

### Nilai Kembali

String yang berisi representasi base-64 yang telah dikodekan dari array input

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) metode

Base-64 mengkodekan rentang elemen dalam byte array yang ditentukan dan mengembalikan data yang telah dikodekan sebagai string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Array byte yang berisi rentang elemen yang akan dikodekan |
| offset_in | int | Indeks elemen dalam array input dimana rentang yang akan dikodekan dimulai |
| length | int | Panjang rentang elemen yang akan dikodekan |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Menentukan opsi pemformatan data yang dikodekan base-64 |

### Nilai Kembali

String yang berisi representasi base-64 yang telah dikodekan dari rentang elemen array input

## Lihat Juga

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [String](../../string/)
* Struktur [Convert](../)
* Namespace [System](../../)
* Pustaka [Aspose.Slides](../../../)