---
title: GetCredential()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie les identifiants pour l'URI spécifié et le type d'authentification.
type: docs
weight: 92
url: /fr/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) method

Renvoie les identifiants pour l'URI spécifié et le type d'authentification.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI. |
| authenticationType | [String](../../../system/string/) | Le type d'authentification. |

## NetworkCredential::GetCredential(String, int32_t, String) method

Renvoie les identifiants pour le nom d'hôte, le port et le type d'authentification spécifiés.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Le nom d'hôte. |
| port | **int32_t** | Le numéro de port. |
| authenticationType | [String](../../../system/string/) | Le type d'authentification. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [NetworkCredential](../)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)