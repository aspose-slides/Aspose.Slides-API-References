---
title: set_RotationAngle()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Specifikuje vlastní otočení, které se aplikuje na text uvnitř ohraničovacího rámečku. Pokud není zadáno, použije se otočení přidruženého tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikováno otočení navíc k tomu, že text samotný má také aplikováno otočení. Výsledná hodnota vizuálního otočení textu je souhrnem této vlastnosti a předdefinovaného svislého typu ve vlastnosti TextVerticalType. Zapisuje se float.
type: docs
weight: 248
url: /cs/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) metoda


Specifikuje vlastní otočení, které se aplikuje na text uvnitř ohraničujícího rámečku. Pokud není zadáno, použije se otočení přidruženého tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikováno otočení kromě toho, že má text také vlastní otočení. Výsledná hodnota vizuálního otočení textu je souhrnem této vlastnosti a předdefinovaného svislého typu v vlastnosti TextVerticalType. Zapisuje se **float**.

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## Poznámky


Zvažte případ, kdy má tvar otočení o 90 stupňů ve směru hodinových ručiček. Navíc má tělo textu otočení o -90 stupňů proti směru hodinových ručiček. Pak se výsledný tvar jeví jako otočený, ale text uvnitř něj se jeví, jako by nebyl vůbec otočen.

## Viz také

* Třída [IChartTextBlockFormat](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)