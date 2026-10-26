---
title: Seek()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la position du flux représenté par l'objet actuel.
type: docs
weight: 183
url: /fr/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(int64_t, IO::SeekOrigin) méthode


Définit la position du flux représenté par l'objet actuel.

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | Le déplacement en octets relatif à une position spécifiée par **origin** |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | Spécifie la position de départ et la direction vers laquelle le déplacement est calculé |

### Valeur de retour

La nouvelle position du flux

## Voir aussi

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Classe [NetworkStream](../)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)