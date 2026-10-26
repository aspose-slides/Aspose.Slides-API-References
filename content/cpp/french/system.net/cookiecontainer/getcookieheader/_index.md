---
title: GetCookieHeader()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un en-tête HTTP contenant les cookies associés à l'URI spécifié.
type: docs
weight: 170
url: /fr/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) méthode

Renvoie un en-tête HTTP contenant les cookies associés à l'URI spécifié.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Un URI pour lequel le nom de l'en-tête sera construit. |

### Valeur de retour

Renvoie un en-tête HTTP contenant les cookies associés à l'URI spécifié.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) méthode

Renvoie un en-tête HTTP contenant les cookies associés à l'URI spécifié.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Un URI pour lequel le nom de l'en-tête sera construit. |
| optCookie2 | [String](../../../system/string/)\& | Le paramètre de sortie où un cookie avec la version maximale prise en charge sera attribué. |

### Valeur de retour

Renvoie un en-tête HTTP contenant les cookies associés à l'URI spécifié.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Uri](../../../system/uri/)
* Classe [CookieContainer](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)