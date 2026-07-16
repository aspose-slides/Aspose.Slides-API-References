---
title: GetCredential()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie les informations d'identification pour le préfixe d'URI spécifié et le type d'authentification.
type: docs
weight: 66
url: /fr/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) méthode

Renvoie les informations d'identification pour le préfixe d'URI spécifié et le type d'authentification.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Le préfixe d'URI. |
| authenticationType | [String](../../../system/string/) | Un type d'authentification. |

## CredentialCache::GetCredential(String, int32_t, String) méthode

Renvoie les informations d'identification pour le nom d'hôte, le port et le type d'authentification spécifiés.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Le nom d'hôte auquel les informations d'identification sont associées. |
| port | **int32_t** | Le numéro de port. |
| authenticationType | [String](../../../system/string/) | Le type d'authentification. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)