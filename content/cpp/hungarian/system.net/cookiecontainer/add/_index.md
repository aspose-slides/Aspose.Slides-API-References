---
title: Add()
second_title: Aspose.Slides for C++ API Referenciája
description: Cookie-t ad a gyűjteményhez.
type: docs
weight: 105
url: /hu/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) metódus

Cookie-t ad a gyűjteményhez.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | A hozzáadandó cookie. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) metódus

Cookie-t ad a gyűjteményhez.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | A hozzáadandó cookie. |
| throwOnError | **bool** | Egy érték, amely azt jelzi, hogy kivétel lesz dobva hiba esetén. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) metódus

A megadott gyűjteményből cookie-kat másol az aktuálisba.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | A gyűjtemény, amelyből a cookie-k másolva lesznek. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) metódus

Cookie-t ad a megadott URI-hez.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A cookie URI-ja. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | A hozzáadandó cookie. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) metódus

A megadott URI-hez a megadott gyűjteményből cookie-kat másol az aktuális gyűjteménybe.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A cookie URI-ja. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Cookie-gyűjtemény, amelyből a cookie-kat másolni kell. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieContainer](../)
* Class [CookieCollection](../../cookiecollection/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)