---
title: GetRangeItemLength()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas RangeItemHeaderValue.
type: docs
weight: 92
url: /id/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) method

Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas [RangeItemHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [String](../../../system/string/) | Sebuah string untuk diparse. |
| startIndex | **int32_t** | Posisi awal untuk parsing. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | Sebuah instance dimana objek yang diparse akan ditempatkan. |

### Nilai Kembali

Mengembalikan panjang substring yang diparse, jika tidak maka 0.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Perpustakaan [Aspose.Slides](../../../)