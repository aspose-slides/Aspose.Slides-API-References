---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Geçilen bir dizeyi NameValueHeaderValue sınıfının bir örneğine dönüştürmeyi dener.
type: docs
weight: 105
url: /tr/system.net.http.headers/namevalueheadervalue/tryparse/
---
## NameValueHeaderValue::TryParse(String, System::SharedPtr\<NameValueHeaderValue\>\&) yöntemi

Geçilen bir dizeyi [NameValueHeaderValue](../) sınıfının bir örneğine dönüştürmeyi dener.

```cpp
static bool System::Net::Http::Headers::NameValueHeaderValue::TryParse(String input, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |

## Dönüş Değeri

True when the parsing is successfully done, otherwise false.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [NameValueHeaderValue](../)
* Ad Alanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)