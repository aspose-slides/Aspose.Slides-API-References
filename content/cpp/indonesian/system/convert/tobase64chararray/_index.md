---
title: ToBase64CharArray()
second_title: Aspose.Slides for C++ Referensi API
description: Base-64 mengkodekan rentang elemen dalam array byte yang ditentukan dan menyimpan data yang dikodekan sebagai array karakter Unicode.
type: docs
weight: 27
url: /id/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) metode


Base-64 mengkodekan rentang elemen dalam array byte yang ditentukan dan menyimpan data yang dikodekan sebagai array karakter Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Array byte yang berisi rentang elemen yang akan dikodekan |
| offset_in | int | Indeks sebuah elemen dalam array masukan di mana rentang yang akan dikodekan dimulai |
| length | int | Panjang rentang elemen yang akan dikodekan |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Referensi konstan ke array keluaran dimana data hasil akan diletakkan |
| offset_out | int | Indeks dalam array keluaran di mana untuk mulai menempatkan data hasil |
| insert_line_breaks | **bool** | Menentukan apakah karakter pemisah baris harus disisipkan dalam array keluaran setelah setiap 76 karakter base-64 |

### Return Value

Jumlah karakter yang ditulis ke array keluaran

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) metode


Base-64 mengkodekan rentang elemen dalam array byte yang ditentukan dan menyimpan data yang dikodekan sebagai array karakter Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Array byte yang berisi rentang elemen yang akan dikodekan |
| offset_in | int | Indeks sebuah elemen dalam array masukan di mana rentang yang akan dikodekan dimulai |
| length | int | Panjang rentang elemen yang akan dikodekan |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Referensi konstan ke array keluaran dimana data hasil akan diletakkan |
| offset_out | int | Indeks dalam array keluaran di mana untuk mulai menempatkan data hasil |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Menentukan opsi format data yang dikodekan base-64 |

### Return Value

Jumlah karakter yang ditulis ke array keluaran

## Lihat Juga

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)