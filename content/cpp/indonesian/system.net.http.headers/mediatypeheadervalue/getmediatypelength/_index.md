---
title: GetMediaTypeLength()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas MediaTypeHeaderValue.
type: docs
weight: 144
url: /id/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) metode


Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | String untuk diparsing. |
| startIndex | **int32_t** | Posisi awal untuk parsing. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | Delegate yang digunakan untuk membuat instance dari kelas [MediaTypeHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Instance dimana objek yang diparsing akan ditetapkan. |

### Nilai Kembali

Mengembalikan panjang substring yang diparsing, jika tidak 0.

## Lihat Juga

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [MediaTypeHeaderValue](../)
* Ruang nama [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)