---
title: AddBlurEffect()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge il nuovo effetto Blur alla fine di una collezione.
type: docs
weight: 157
url: /it/aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) method


Aggiunge il nuovo effetto [Blur](../../blur/) alla fine di una collezione.

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radius | **double** | Il raggio della sfocatura. |
| grow | **bool** | Specifica se i limiti dell'oggetto devono essere ingranditi a seguito della sfocatura. True indica che i limiti sono ingranditi mentre false indica che non lo sono. |

### Valore restituito

Indice del nuovo effetto immagine nella collezione.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBlur](../../iblur/)
* Classe [ImageTransformOperationCollection](../)
* Spazio dei nomi [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)