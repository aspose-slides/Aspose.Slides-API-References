---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en cookie i samlingen.
type: docs
weight: 105
url: /sv/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) metod


Lägger till en cookie i samlingen.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookien att lägga till. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) metod


Lägger till en cookie i samlingen.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookien att lägga till. |
| throwOnError | **bool** | Ett värde som indikerar om ett undantag kommer att kastas när ett fel uppstår. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) metod


Kopierar cookies från den angivna samlingen till den aktuella.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Samlingen från vilken cookies kommer att kopieras. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) metod


Lägger till en cookie för den angivna URI:n.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | En URI för cookien. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookien att lägga till. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) metod


Kopierar cookies från den angivna samlingen för den angivna URI:n till den aktuella samlingen.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | En URI för cookien. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | En cookie collection från vilken cookies måste kopieras. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieContainer](../)
* Class [CookieCollection](../../cookiecollection/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)