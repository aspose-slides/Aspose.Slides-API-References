---
title: GetNameValueListLength()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen indeksten bir dizeyi NameValueHeaderValue-class örneklerinin koleksiyonuna dönüştürür ve ayrıştırılmış bir alt dizenin uzunluğunu döndürür.
type: docs
weight: 131
url: /tr/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) metod

Belirtilen indeksten itibaren verilen dizeyi NameValueHeaderValue-class örneklerinin koleksiyonuna dönüştürür ve ayrıştırılmış bir alt dizenin uzunluğunu döndürür.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Analiz edilecek bir dize. |
| startIndex | **int32_t** | Analiz için bir başlangıç konumu. |
| delimiter | char16_t | Belirtilen dizedeki öğeleri ayırmak için kullanılan bir dize. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Ayrıştırılmış bir koleksiyonun atanacağı çıktı parametresi. |

### Dönüş Değeri

Ayrıştırılmış bir alt dizenin uzunluğu.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ObjectCollection](../../objectcollection/)
* Sınıf [NameValueHeaderValue](../)
* Ad alanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)