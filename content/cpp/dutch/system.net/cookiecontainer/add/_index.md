---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een cookie toe aan de collectie.
type: docs
weight: 105
url: /nl/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) methode

Voegt een cookie toe aan de collectie.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | De cookie om toe te voegen. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) methode

Voegt een cookie toe aan de collectie.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | De cookie om toe te voegen. |
| throwOnError | **bool** | Een waarde die aangeeft of een uitzondering wordt gegooid wanneer een fout optreedt. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) methode

Kopieert cookies van de opgegeven collectie naar de huidige.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | De collectie waaruit cookies gekopieerd worden. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) methode

Voegt een cookie toe voor de opgegeven URI.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Een URI van de cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | De cookie om toe te voegen. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) methode

Kopieert cookies van de opgegeven collectie voor de opgegeven URI naar de huidige collectie.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Een URI van de cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Een cookie-collectie waarvan cookies moeten worden gekopieerd. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Cookie](../../cookie/)
* Klasse [CookieContainer](../)
* Klasse [CookieCollection](../../cookiecollection/)
* Klasse [Uri](../../../system/uri/)
* Naamruimte [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)