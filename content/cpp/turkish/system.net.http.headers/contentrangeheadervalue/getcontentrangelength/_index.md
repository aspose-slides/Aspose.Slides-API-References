---
title: GetContentRangeLength()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen konumdaki geçilen dizeyi ContentRangeHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 170
url: /tr/system.net.http.headers/contentrangeheadervalue/getcontentrangelength/
---
## ContentRangeHeaderValue::GetContentRangeLength(String, int32_t, System::SharedPtr\<Object\>\&) metodu


Geçirilen bir dizgiyi belirtilen konumdan [ContentRangeHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::ContentRangeHeaderValue::GetContentRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için başlangıç konumu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Ayrıştırılmış nesnenin atanacağı örnek. |

### Dönüş Değeri

Ayrıştırılan alt dizenin uzunluğu, aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [ContentRangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)