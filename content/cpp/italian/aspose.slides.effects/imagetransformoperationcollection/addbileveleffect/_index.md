---
title: AddBiLevelEffect()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge il nuovo effetto Bi-Level (nero/bianco) alla fine di una raccolta.
type: docs
weight: 144
url: /it/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) metodo


Aggiunge il nuovo effetto Bi-Level (nero/bianco) alla fine di una raccolta.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | **float** | la soglia di luminanza per l'effetto Bi-Level. I valori maggiori o uguali alla soglia sono impostati su bianco. I valori inferiori alla soglia sono impostati su nero. |

### Valore restituito

Indice del nuovo effetto immagine in una raccolta.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBiLevel](../../ibilevel/)
* Classe [ImageTransformOperationCollection](../)
* Spazio dei nomi [Aspose::Slides::Effects](../../)
* Libreria [Aspose.Slides](../../../)