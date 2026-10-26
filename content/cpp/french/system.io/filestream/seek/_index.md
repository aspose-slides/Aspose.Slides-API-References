---
title: Seek()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la position du flux représenté par l'objet actuel.
type: docs
weight: 209
url: /fr/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) méthode

Définit la position du flux représenté par l'objet actuel.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | Le décalage en octets par rapport à une position spécifiée par **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | Spécifie la position à partir de laquelle et la direction vers laquelle le décalage est calculé. |

### Valeur de retour

La nouvelle position du flux.

## Voir aussi

* Énumération [SeekOrigin](../../seekorigin/)
* Classe [FileStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)