---
title: GetNameValueLength()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas NameValueHeaderValue.
type: docs
weight: 118
url: /id/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) metode

Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [String](../../../system/string/) | String untuk diparse. |
| startIndex | **int32_t** | Posisi awal untuk parsing. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Sebuah instance dimana objek yang diparse akan ditempatkan. |

### Nilai Kembali

Mengembalikan panjang substring yang diparse, atau 0 jika tidak.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) metode

Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [String](../../../system/string/) | String untuk diparse. |
| startIndex | **int32_t** | Posisi awal untuk parsing. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Fungsi yang digunakan untuk membuat instance baru dari kelas [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Sebuah instance dimana objek yang diparse akan ditempatkan. |

### Nilai Kembali

Mengembalikan panjang substring yang diparse, atau 0 jika tidak.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Kelas [String](../../../system/string/)
* Kelas [NameValueHeaderValue](../)
* Ruang Nama [System::Net::Http::Headers](../../)
* Perpustakaan [Aspose.Slides](../../../)