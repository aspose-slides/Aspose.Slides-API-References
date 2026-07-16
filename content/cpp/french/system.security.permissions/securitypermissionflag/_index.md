---
title: SecurityPermissionFlag
second_title: Référence de l'API Aspose.Slides pour C++
description: Indicateurs d'autorisation de sécurité.
type: docs
weight: 27
url: /fr/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Indicateurs d'autorisation de sécurité.

```cpp
enum class SecurityPermissionFlag
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NoFlags | 0 | Pas d'accès. |
| Assertion | 1 | Affirmer que l'autorisation est accordée. |
| UnmanagedCode | 2 | Appeler du code non géré. |
| SkipVerification | 4 | Ignorer la vérification du code. |
| Execution | 8 | Exécuter le code. |
| ControlThread | 16 | Effectuer des opérations sur les threads. |
| ControlEvidence | 32 | Contrôler ou modifier les preuves CLR. |
| ControlPolicy | 64 | Afficher et modifier la politique. |
| SerializationFormatter | 128 | Sérialiser. |
| ControlDomainPolicy | 256 | Définir la politique du domaine. |
| ControlPrincipal | 512 | Contrôler l'objet principal. |
| ControlAppDomain | 1024 | Contrôler le domaine d'application. |
| RemotingConfiguration | 2048 | Configurer le remoting. |
| Infrastructure | 4096 | Se brancher à l'infrastructure CLR. |
| BindingRedirects | 8192 | Effectuer une redirection explicite de liaison. |
| AllFlags | 16383 | Illimité. |

## Voir aussi

* Espace de noms [System::Security::Permissions](../)
* Bibliothèque [Aspose.Slides](../../)