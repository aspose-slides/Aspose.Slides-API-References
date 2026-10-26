---
title: AddBiLevelEffect()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový Bi-Level (černá/bílá) efekt na konec kolekce.
type: docs
weight: 144
url: /cs/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) metoda

Přidá nový Bi-Level (černá/bílá) efekt na konec kolekce.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | **float** | luminanční threshold pro efekt Bi-Level. Hodnoty větší nebo rovné threshold jsou nastaveny na bílou. Hodnoty menší než threshold jsou nastaveny na černou. |

### Návratová hodnota

Index nového efektu obrazu v kolekci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IBiLevel](../../ibilevel/)
* Třída [ImageTransformOperationCollection](../)
* Jmenný prostor [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)