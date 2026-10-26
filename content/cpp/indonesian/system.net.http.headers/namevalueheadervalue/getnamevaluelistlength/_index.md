---
title: GetNameValueListLength()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang diberikan dari indeks yang ditentukan ke koleksi instansi kelas NameValueHeaderValue dan mengembalikan panjang substring yang diurai.
type: docs
weight: 131
url: /id/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) method


Mengonversi string yang diberikan dari indeks yang ditentukan ke koleksi instansi kelas NameValueHeaderValue dan mengembalikan panjang substring yang diurai.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [String](../../../system/string/) | Sebuah string untuk dianalisis. |
| startIndex | **int32_t** | Posisi awal untuk analisis. |
| delimiter | char16_t | String yang digunakan untuk memisahkan item dalam string yang ditentukan. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Parameter keluaran di mana koleksi yang diurai akan ditempatkan. |

### Nilai Kembali

Panjang substring yang diurai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)