---
title: SocketType
second_title: Référence de l'API Aspose.Slides pour C++
description: Énumère les types de socket.
type: docs
weight: 131
url: /fr/system.net.sockets/sockettype/
---
## SocketType enum

Énumère les types de socket.

```cpp
enum class SocketType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Stream | 1 | Le type qui prend en charge des flux d’octets fiables, bidirectionnels, basés sur une connexion, sans duplication de données et sans préservation des limites. |
| Dgram | 2 | Le type qui prend en charge les datagrammes, qui sont des messages sans connexion, peu fiables, d’une longueur maximale fixe. |
| Raw | 3 | Le type qui permet l’accès au protocole de transport sous-jacent. |
| Rdm | 4 | Le type qui prend en charge des messages sans connexion, orientés message, livrés de manière fiable, et qui préserve les limites des messages dans les données. |
| Seqpacket | 5 | Le type qui fournit un transfert bidirectionnel, orienté connexion et fiable de flux d’octets ordonnés à travers un réseau. |
| Unknown | n/a | Un type inconnu. |

## Voir aussi

* Espace de noms [System::Net::Sockets](../)
* Bibliothèque [Aspose.Slides](../../)