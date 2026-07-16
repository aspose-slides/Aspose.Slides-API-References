---
title: CreateHttp()
second_title: Référence API Aspose.Slides pour C++
description: Crée une nouvelle instance de la classe WebRequest en utilisant l'URI spécifié.
type: docs
weight: 79
url: /fr/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) méthode

Crée une nouvelle instance de la classe [WebRequest](../) en utilisant l'URI spécifié.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | L'URI utilisé pour créer une nouvelle instance de la classe [WebRequest](../). |

### Valeur de retour

Une instance de classe WebRequest nouvellement créée.

## Remarques

Une NotSupportedException sera levée lorsque l'URI spécifié commence par un schéma autre que [http://](http://) ou [https://](https://). 

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) méthode

Crée une nouvelle instance de la classe [WebRequest](../) en utilisant l'URI spécifié.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI utilisé pour créer une nouvelle instance de la classe [WebRequest](../). |

### Valeur de retour

Une instance de classe WebRequest nouvellement créée.

## Remarques

Une NotSupportedException sera levée lorsque l'URI spécifié commence par un schéma autre que [http://](http://) ou [https://](https://). 

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpWebRequest](../../httpwebrequest/)
* Classe [String](../../../system/string/)
* Classe [WebRequest](../)
* Classe [Uri](../../../system/uri/)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)