---
title: GetTransferCodingLength()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen indeksden geçirilen bir dizeyi TransferCodingHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 105
url: /tr/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) yöntemi

Belirtilen indeksden geçen bir dizeyi [TransferCodingHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için başlangıç konumu. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | [TransferCodingHeaderValue](../) sınıfının örneklerini oluşturmak için kullanılan temsilci. |

### Dönüş Değeri

Ayrıştırılmış bir alt dizenin uzunluğunu döndürür, aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [TransferCodingHeaderValue](../)
* Ad Alanı [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)