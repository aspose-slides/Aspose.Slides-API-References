---
title: Seek()
second_title: "Référence de l'API Aspose.Slides pour C++"
description: "Définit la position du flux représenté par l'objet actuel."
type: docs
weight: 40
url: /fr/system.io/stdiostreamwrapperbase/seek/
---
## STDIOStreamWrapperBase::Seek(int64_t, SeekOrigin) method

Définit la position du flux représenté par l’objet actuel.

```cpp
virtual int64_t System::IO::STDIOStreamWrapperBase<T, typename>::Seek(int64_t offset, SeekOrigin origin) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | Le déplacement en octets par rapport à une position spécifiée par **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Spécifie la position à partir de laquelle et la direction vers laquelle le déplacement est calculé |

### Valeur de retour

La nouvelle position du flux

## Voir aussi

* Enum [SeekOrigin](../../seekorigin/)
* Classe [STDIOStreamWrapperBase](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)