---
title: GetEntityTagLength()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen indeksden verilen dizeyi EntityTagHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 118
url: /tr/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) yöntemi

Belirtilen indeksteki verilen dizgiyi [EntityTagHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için başlangıç konumu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |

### Dönüş Değeri

Ayrıştırılmış alt dizgenin uzunluğu, aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [EntityTagHeaderValue](../)
* Ad alanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)