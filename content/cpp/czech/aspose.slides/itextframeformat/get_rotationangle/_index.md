---
title: get_RotationAngle()
second_title: Aspose.Slides pro C++ - reference API
description: Určuje vlastní otočení, které se použije na text uvnitř ohraničovacího rámečku. Pokud není zadáno, použije se otočení odpovídajícího tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikováno otočení a zároveň může mít text vlastní otočení. Výsledná hodnota vizuálního otočení textu je shrnuta z této vlastnosti a předdefinovaného svislého typu ve vlastnosti TextVerticalType. Vrací float.
type: docs
weight: 339
url: /cs/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() metoda


Určuje vlastní otočení, které se použije na text uvnitř ohraničujícího rámce. Pokud není zadáno, použije se otočení odpovídajícího tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikováno otočení a zároveň může mít text vlastní otočení. Výsledná hodnota vizuálního otočení textu je shrnuta z této vlastnosti a předdefinovaného svislého typu ve vlastnosti TextVerticalType. Vrací **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## Poznámky


Uvažujme případ, kdy má tvar aplikované otočení o 90 stupňů po směru hodinových ručiček. K tomu je tělu textu aplikováno otočení o -90 stupňů proti směru hodinových ručiček. Výsledný tvar bude vypadat otočený, ale text uvnitř něj se bude jevit, jako kdyby nebyl vůbec otočen. 

## Viz také

* Třída [ITextFrameFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)