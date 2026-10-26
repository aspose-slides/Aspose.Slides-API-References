---
title: GetCookieHeader()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen HTTP-Header zurück, der Cookies enthält, die mit der angegebenen URI verbunden sind.
type: docs
weight: 170
url: /de/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) Methode

Gibt einen HTTP-Header zurück, der Cookies enthält, die mit der angegebenen URI verbunden sind.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Eine URI, für die der Header-Name erstellt wird. |

### Rückgabewert

Ein HTTP-Header, der Cookies enthält, die mit der angegebenen URI verbunden sind.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) Methode

Gibt einen HTTP-Header zurück, der Cookies enthält, die mit der angegebenen URI verbunden sind.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Eine URI, für die der Header-Name erstellt wird. |
| optCookie2 | [String](../../../system/string/)\& | Der Ausgabeparameter, dem ein Cookie mit der maximal unterstützten Version zugewiesen wird. |

### Rückgabewert

Ein HTTP-Header, der Cookies enthält, die mit der angegebenen URI verbunden sind.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Uri](../../../system/uri/)
* Klasse [CookieContainer](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)