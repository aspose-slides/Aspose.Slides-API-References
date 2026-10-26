---
title: Seek()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la position dans le flux actuel
type: docs
weight: 131
url: /fr/aspose.slides/istreamwrapper/seek/
---
## IStreamWrapper::Seek(int64_t, System::IO::SeekOrigin) méthode

Définit la position dans le flux actuel

```cpp
virtual int64_t Aspose::Slides::IStreamWrapper::Seek(int64_t offset, System::IO::SeekOrigin origin)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | Un décalage en octets relatif au paramètre origin **int64_t** |
| origin | [System::IO::SeekOrigin](../../../system.io/seekorigin/) | Une valeur de type [System::IO::SeekOrigin](../../../system.io/seekorigin/) indiquant le point de référence utilisé pour obtenir la nouvelle position |

### Valeur de retour

La nouvelle position dans le flux actuel **int64_t**

## Voir aussi

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Classe [IStreamWrapper](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)