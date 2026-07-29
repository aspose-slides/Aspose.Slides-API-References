---
title: GetCookieHeader()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en HTTP-header som innehåller kakor som är associerade med den angivna URI:n.
type: docs
weight: 170
url: /sv/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) metod


Returnera en HTTP-header som innehåller kakor som är associerade med den angivna URI:n.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | En URI för vilken headernamn kommer att byggas. |

### Returvärde

En HTTP-header som innehåller kakor som är associerade med den angivna URI:n.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) metod


Returnera en HTTP-header som innehåller kakor som är associerade med den angivna URI:n.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | En URI för vilken headernamn kommer att byggas. |
| optCookie2 | [String](../../../system/string/)\& | Utdata-parametern där en kaka med den högsta stödda versionen kommer att tilldelas. |

### Returvärde

En HTTP-header som innehåller kakor som är associerade med den angivna URI:n.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Uri](../../../system/uri/)
* Klass [CookieContainer](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)