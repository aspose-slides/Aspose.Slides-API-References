---
title: Seek()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la position du flux représenté par l'objet actuel.
type: docs
weight: 105
url: /fr/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) méthode


Définit la position du flux représenté par l'objet actuel.

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | Le décalage en octets relatif à une position spécifiée par **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Spécifie la position à partir de laquelle et la direction vers laquelle le décalage est calculé |

### Valeur de retour

La nouvelle position du flux

## Voir aussi

* Enum [SeekOrigin](../../seekorigin/)
* Classe [MemoryStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)