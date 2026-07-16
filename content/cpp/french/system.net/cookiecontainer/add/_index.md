---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un cookie à la collection.
type: docs
weight: 105
url: /fr/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) method


Ajoute un cookie à la collection.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | The cookie to add. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) method


Ajoute un cookie à la collection.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | The cookie to add. |
| throwOnError | **bool** | Valeur indiquant si une exception sera levée lorsqu'une erreur se produit. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) method


Copie les cookies de la collection spécifiée vers celle actuelle.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | The collection from which cookies will be copied. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) method


Ajoute un cookie pour l'URI spécifié.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | An URI of the cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | The cookie to add. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) method


Copie les cookies de la collection spécifiée pour l'URI spécifiée vers la collection actuelle.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | An URI of the cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | A cookie collection from which cookies must be copied. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Cookie](../../cookie/)
* Classe [CookieContainer](../)
* Classe [CookieCollection](../../cookiecollection/)
* Classe [Uri](../../../system/uri/)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)