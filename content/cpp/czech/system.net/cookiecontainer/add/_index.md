---
title: Add()
second_title: Aspose.Slides pro C++ referenci API
description: Přidá cookie do kolekce.
type: docs
weight: 105
url: /cs/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) metoda


Přidá cookie do kolekce.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie, která se má přidat. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) metoda


Přidá cookie do kolekce.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie, která se má přidat. |
| throwOnError | **bool** | Hodnota, která určuje, zda bude při výskytu chyby vyvolána výjimka. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) metoda


Zkopíruje cookies ze specifikované kolekce do aktuální.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Kolekce, ze které budou cookies zkopírovány. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) metoda


Přidá cookie pro zadané URI.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie, která se má přidat. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) metoda


Zkopíruje cookies ze specifikované kolekce pro zadané URI do aktuální kolekce.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Kolekce cookies, ze které je třeba cookies zkopírovat. |

## Viz také

* typedef [SharedPtr](../../../system/sharedptr/)
* třída [Cookie](../../cookie/)
* třída [CookieContainer](../)
* třída [CookieCollection](../../cookiecollection/)
* třída [Uri](../../../system/uri/)
* jmenný prostor [System::Net](../../)
* knihovna [Aspose.Slides](../../../)