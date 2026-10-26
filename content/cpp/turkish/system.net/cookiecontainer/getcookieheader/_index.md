---
title: GetCookieHeader()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URI ile ilişkili çerezleri içeren bir HTTP başlığı döndürür.
type: docs
weight: 170
url: /tr/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) metot

Belirtilen URI ile ilişkili çerezleri içeren bir HTTP başlığı döndürür.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Başlık adı oluşturulacak URI. |

### Dönüş Değeri

Belirtilen URI ile ilişkili çerezleri içeren bir HTTP başlığı.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) metot

Belirtilen URI ile ilişkili çerezleri içeren bir HTTP başlığı döndürür.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Başlık adı oluşturulacak URI. |
| optCookie2 | [String](../../../system/string/)\& | En yüksek desteklenen sürümdeki bir çerezin atanacağı çıkış parametresi. |

### Dönüş Değeri

Belirtilen URI ile ilişkili çerezleri içeren bir HTTP başlığı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [CookieContainer](../)
* Ad alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)