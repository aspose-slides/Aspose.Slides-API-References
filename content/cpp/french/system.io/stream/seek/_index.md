---
title: Seek()
second_title: Référence de l'API Aspose.Slides for C++
description: Définit la position du flux représenté par l'objet actuel.
type: docs
weight: 79
url: /fr/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) method


Définit la position du flux représenté par l'objet actuel.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | Le décalage en octets par rapport à une position spécifiée par **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Spécifie la position à partir de laquelle et la direction vers laquelle le décalage est calculé |

### Valeur de retour

La nouvelle position du flux

## Voir aussi

* Enum [SeekOrigin](../../seekorigin/)
* Classe [Stream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)