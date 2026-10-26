---
title: GetCookieHeader()
second_title: Aspose.Slides pro C++ API Reference
description: Vrátí HTTP hlavičku, která obsahuje cookies spojené se zadaným URI.
type: docs
weight: 170
url: /cs/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) metoda

Vrátí HTTP hlavičku, která obsahuje cookies přidružené k zadanému URI.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, pro které bude vytvořen název hlavičky. |

### Návratová hodnota

HTTP hlavička, která obsahuje cookies přidružené k zadanému URI.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) metoda

Vrátí HTTP hlavičku, která obsahuje cookies přidružené k zadanému URI.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, pro které bude vytvořen název hlavičky. |
| optCookie2 | [String](../../../system/string/)\& | Výstupní parametr, do kterého bude přiřazena cookie s maximální podporovanou verzí. |

### Návratová hodnota

HTTP hlavička, která obsahuje cookies přidružené k zadanému URI.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Uri](../../../system/uri/)
* Třída [CookieContainer](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)