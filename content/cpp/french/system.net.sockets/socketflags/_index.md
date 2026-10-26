---
title: SocketFlags
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit des valeurs constantes pour les messages du socket.
type: docs
weight: 222
url: /fr/system.net.sockets/socketflags/
---
## SocketFlags enum

Fournit des valeurs constantes pour les messages du socket.

```cpp
enum class SocketFlags
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Aucun indicateur n'est utilisé pour cet appel. |
| OutOfBand | 1 | Les données hors bande sont en cours de traitement. |
| Peek | 2 | Inspecter un message entrant. |
| DontRoute | 4 | Envoyer un message sans utiliser les tables de routage. |
| Truncated | 256 | Un message est trop volumineux pour tenir dans le tampon spécifié. Il a été tronqué. |
| ControlDataTruncated | 512 | Les données de contrôle dépassent 64 KB et ne tiennent pas dans le tampon interne. Elles ont été tronquées. |
| Broadcast | 1024 | Un paquet de diffusion. |
| Multicast | 2048 | Un paquet multicast. |
| Partial | 32768 | Un message envoyé ou reçu partiellement. |

## Voir aussi

* Espace de noms [System::Net::Sockets](../)
* Bibliothèque [Aspose.Slides](../../)