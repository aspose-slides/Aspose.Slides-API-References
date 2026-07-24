---
title: GetNameValueLength()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen indeksden gelen bir dizeyi NameValueHeaderValue sınıfının bir örneğine dönüştürür.
type: docs
weight: 118
url: /tr/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) metodu

Belirtilen indeksden başlayan bir dizeyi [NameValueHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için başlangıç konumu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |

### Dönüş Değeri

Ayrıştırılmış bir alt dizenin uzunluğunu döndürür, aksi takdirde 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) metodu

Belirtilen indeksden başlayan bir dizeyi [NameValueHeaderValue](../) sınıfının bir örneğine dönüştürür.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ayrıştırılacak bir dize. |
| startIndex | **int32_t** | Ayrıştırma için başlangıç konumu. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | [NameValueHeaderValue](../) sınıfının yeni örneklerini oluşturmak için kullanılan bir işlev. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Ayrıştırılmış bir nesnenin atanacağı bir örnek. |

### Dönüş Değeri

Ayrıştırılmış bir alt dizenin uzunluğunu döndürür, aksi takdirde 0.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Sınıf [String](../../../system/string/)
* Sınıf [NameValueHeaderValue](../)
* Ad alanı [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)