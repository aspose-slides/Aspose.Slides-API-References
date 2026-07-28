---
title: GetCookieHeader()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Zwraca nagłówek HTTP zawierający ciasteczka powiązane z podanym adresem URI.
type: docs
weight: 170
url: /pl/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) metoda


Zwraca nagłówek HTTP zawierający ciasteczka powiązane z podanym adresem URI.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adres URI, dla którego zostanie zbudowana nazwa nagłówka. |

### Wartość zwracana

Nagłówek HTTP zawierający ciasteczka powiązane z podanym adresem URI.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) metoda


Zwraca nagłówek HTTP zawierający ciasteczka powiązane z podanym adresem URI.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adres URI, dla którego zostanie zbudowana nazwa nagłówka. |
| optCookie2 | [String](../../../system/string/)\& | Parametr wyjściowy, do którego zostanie przypisane ciasteczko z maksymalną obsługiwaną wersją. |

### Wartość zwracana

Nagłówek HTTP zawierający ciasteczka powiązane z podanym adresem URI.

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Uri](../../../system/uri/)
* Class [CookieContainer](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)