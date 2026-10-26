---
title: Remove()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime les informations d'identification réseau pour le préfixe URI spécifié et le type d'authentification.
type: docs
weight: 53
url: /fr/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) méthode


Supprime les informations d’identification réseau pour le préfixe URI spécifié et le type d’authentification.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Le préfixe URI. |
| authenticationType | [String](../../../system/string/) | Le type d’authentification. |

## CredentialCache::Remove(String, int32_t, String) méthode


Supprime les informations d’identification réseau pour le nom d’hôte, le port et le type d’authentification spécifiés.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Le nom d’hôte auquel les informations d’identification sont associées. |
| port | **int32_t** | Le numéro de port. |
| authenticationType | [String](../../../system/string/) | Un type d’authentification. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [CredentialCache](../)
* Espace de noms [System::Net](../../)
* Library [Aspose.Slides](../../../)