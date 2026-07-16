---
title: WebExceptionStatus
second_title: Référence API Aspose.Slides pour C++
description: Énumère les codes d'état de la classe WebException.
type: docs
weight: 651
url: /fr/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Énumère les codes d'état de la classe WebException.

```cpp
enum class WebExceptionStatus
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Success | 0 | Aucune erreur n'est survenue. |
| NameResolutionFailure | 1 | Le service de résolution de noms n'a pas pu résoudre le nom d'hôte. |
| ConnectFailure | 2 | Le point de service distant n'a pas pu être contacté au niveau du transport. |
| ReceiveFailure | 3 | Une réponse complète n'a pas été reçue du serveur distant. |
| SendFailure | 4 | Une requête complète n'a pas pu être envoyée au serveur distant. |
| PipelineFailure | 5 | La requête était une requête en pipeline et la connexion a été fermée avant la réception de la réponse. |
| RequestCanceled | 6 | La requête a été annulée ou une erreur non classifiable s'est produite. |
| ProtocolError | 7 | La réponse reçue du serveur était complète mais indiquait une erreur au niveau du protocole. |
| ConnectionClosed | 8 | La connexion a été fermée prématurément. |
| TrustFailure | 9 | Un certificat serveur n'a pas pu être validé. |
| SecureChannelFailure | 10 | Une erreur s'est produite lors de l'établissement d'une connexion SSL. |
| ServerProtocolViolation | 11 | La réponse du serveur n'était pas une réponse HTTP valide. |
| KeepAliveFailure | 12 | La connexion pour une requête spécifiant l'en-tête 'Keep-Alive' a été fermée de manière inattendue. |
| Pending | 13 | Une requête asynchrone interne est en attente. |
| Timeout | 14 | Aucune réponse n'a été reçue pendant la période d'expiration d'une requête. |
| ProxyNameResolutionFailure | 15 | Le service de résolution de noms n'a pas pu résoudre le nom d'hôte du proxy. |
| UnknownError | 16 | Une exception de type inconnu s'est produite. |
| MessageLengthLimitExceeded | 17 | Un message dépassant la limite spécifiée a été reçu. |
| CacheEntryNotFound | 18 | L'entrée de cache spécifiée est introuvable. |
| RequestProhibitedByCachePolicy | 19 | La requête n'était pas autorisée par la politique de cache. |
| RequestProhibitedByProxy | 20 | Cette requête n'était pas autorisée par le proxy. |

## Voir aussi

* Espace de noms [System::Net](../)
* Bibliothèque [Aspose.Slides](../../)