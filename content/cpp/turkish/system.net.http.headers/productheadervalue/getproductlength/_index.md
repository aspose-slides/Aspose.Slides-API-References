---
title: GetProductLength()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen indeksten geçen bir dizeyi ProductHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 105
url: /tr/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) metod


Belirtilen indeksden geçen bir dizeyi [ProductHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için bir başlangıç konumu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |

### Return Value

Ayrıştırılmış bir alt dizenin uzunluğunu döndürür; aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ProductHeaderValue](../)
* Ad Alanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)