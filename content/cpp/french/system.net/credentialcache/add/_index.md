---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute les informations d'identification réseau spécifiées au cache.
type: docs
weight: 40
url: /fr/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) méthode


Ajoute les informations d'identification réseau spécifiées au cache.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Le préfixe URI de la ressource avec lequel les informations d'identification sont associées. |
| authenticationType | [String](../../../system/string/) | Le schéma d'authentification. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Les informations d'identification à ajouter. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) méthode


Ajoute les informations d'identification réseau spécifiées au cache.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Le nom d'hôte avec lequel les informations d'identification sont associées. |
| port | **int32_t** | Le numéro de port. |
| authenticationType | [String](../../../system/string/) | Le schéma d'authentification. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Les informations d'identification à ajouter. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [NetworkCredential](../../networkcredential/)
* Classe [CredentialCache](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)