---
title: GetCredential()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie les informations d'identification pour l'hôte spécifié et le type d'authentification.
type: docs
weight: 1
url: /fr/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) method

Renvoie les informations d'identification pour l'hôte spécifié et le type d'authentification.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | L'hôte qui authentifie le client. |
| port | **int32_t** | Le numéro de port de l'hôte. |
| authenticationType | [String](../../../system/string/) | Le type d'authentification. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [NetworkCredential](../../networkcredential/)
* Classe [String](../../../system/string/)
* Classe [ICredentialsByHost](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)