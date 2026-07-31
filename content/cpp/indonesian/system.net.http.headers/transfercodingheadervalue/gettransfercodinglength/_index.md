---
title: GetTransferCodingLength()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas TransferCodingHeaderValue.
type: docs
weight: 105
url: /id/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) method


Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [String](../../../system/string/) | Sebuah string untuk diurai. |
| startIndex | **int32_t** | Posisi awal untuk parsing. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Sebuah instance dimana objek yang diurai akan ditempatkan. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Delegasi yang digunakan untuk membuat instance kelas [TransferCodingHeaderValue](../). |

### Nilai Kembali

Mengembalikan panjang substring yang diurai, jika tidak 0.

## Lihat Juga

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Perpustakaan [Aspose.Slides](../../../)