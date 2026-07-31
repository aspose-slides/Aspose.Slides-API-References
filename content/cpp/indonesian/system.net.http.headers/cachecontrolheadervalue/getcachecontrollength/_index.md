---
title: GetCacheControlLength()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas CacheControlHeaderValue.
type: docs
weight: 456
url: /id/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) metode

Mengonversi string yang diteruskan dari indeks yang ditentukan menjadi sebuah instance dari kelas [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [String](../../../system/string/) | String untuk diparse. |
| startIndex | **int32_t** | Posisi awal untuk parsing. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Nilai yang harus ditambahkan ke objek yang diparse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Instance dimana objek yang diparse akan ditempatkan. |

### Nilai Kembalian

Panjang substring yang diparse, jika tidak 0.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [CacheControlHeaderValue](../)
* Ruang Nama [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)