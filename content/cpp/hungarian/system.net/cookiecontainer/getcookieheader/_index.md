---
title: GetCookieHeader()
second_title: Aspose.Slides for C++ API referenciája
description: Visszaad egy HTTP-fejlécet, amely a megadott URI-hez tartozó sütiket tartalmazza.
type: docs
weight: 170
url: /hu/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) metódus

Visszaad egy HTTP-fejlécet, amely a megadott URI-hez tartozó sütiket tartalmazza.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Egy URI, amelyhez a fejléc nevét felépítik. |

### Visszatérési érték

Egy HTTP-fejléc, amely a megadott URI-hez tartozó sütiket tartalmazza.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) metódus

Visszaad egy HTTP-fejlécet, amely a megadott URI-hez tartozó sütiket tartalmazza.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Egy URI, amelyhez a fejléc nevét felépítik. |
| optCookie2 | [String](../../../system/string/)\& | A kimeneti paraméter, amelyhez a legmagasabb támogatott verziójú süti lesz hozzárendelve. |

### Visszatérési érték

Egy HTTP-fejléc, amely a megadott URI-hez tartozó sütiket tartalmazza.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Uri](../../../system/uri/)
* Osztály [CookieContainer](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)