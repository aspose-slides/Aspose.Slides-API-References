---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Cookie zur Sammlung hinzu.
type: docs
weight: 105
url: /de/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) Methode

Fügt ein Cookie zur Sammlung hinzu.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Das Cookie, das hinzugefügt werden soll. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) Methode

Fügt ein Cookie zur Sammlung hinzu.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Das Cookie, das hinzugefügt werden soll. |
| throwOnError | **bool** | Ein Wert, der angibt, ob bei einem Fehler eine Ausnahme ausgelöst wird. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) Methode

Kopiert Cookies aus der angegebenen Sammlung in die aktuelle.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Die Sammlung, aus der Cookies kopiert werden. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) Methode

Fügt ein Cookie für die angegebene URI hinzu.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Eine URI des Cookies. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Das Cookie, das hinzugefügt werden soll. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) Methode

Kopiert Cookies aus der angegebenen Sammlung für die angegebene URI in die aktuelle Sammlung.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Eine URI des Cookies. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Eine Cookie-Sammlung, aus der Cookies kopiert werden. |

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Cookie](../../cookie/)
* Klasse [CookieContainer](../)
* Klasse [CookieCollection](../../cookiecollection/)
* Klasse [Uri](../../../system/uri/)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)