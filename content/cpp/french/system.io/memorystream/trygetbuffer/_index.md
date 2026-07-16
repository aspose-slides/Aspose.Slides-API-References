---
title: TryGetBuffer()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie le tableau d'octets non signés à partir duquel ce flux a été créé.
type: docs
weight: 170
url: /fr/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) méthode

Renvoie le tableau d'octets non signés à partir duquel ce flux a été créé.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | tableau d'octets - paramètre de sortie. Lorsque cette méthode renvoie true, le segment de tableau d'octets à partir duquel ce flux a été créé ; lorsque cette méthode renvoie false, ce paramètre est défini à la valeur par défaut. |

### Valeur de retour

True si la conversion a réussi.

## Voir aussi

* Classe [ArraySegment](../../../system/arraysegment/)
* Classe [MemoryStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)