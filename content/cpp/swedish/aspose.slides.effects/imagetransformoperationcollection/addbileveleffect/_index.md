---
title: AddBiLevelEffect()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till den nya Bi-Level (svart/vitt) effekten i slutet av en samling.
type: docs
weight: 144
url: /sv/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) metod


Lägger till den nya Bi-Level (svart/vitt) effekten i slutet av en samling.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | **float** | ljushetströskeln för Bi-Level-effekten. Värden som är större än eller lika med tröskeln sätts till vitt. Värden som är mindre än tröskeln sätts till svart. |

### Returvärde

Index för den nya bildeffekten i en samling.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IBiLevel](../../ibilevel/)
* Klass [ImageTransformOperationCollection](../)
* Namnrymd [Aspose::Slides::Effects](../../)
* Bibliotek [Aspose.Slides](../../../)