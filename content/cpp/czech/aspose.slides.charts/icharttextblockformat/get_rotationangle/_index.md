---
title: get_RotationAngle()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. Pokud není zadáno, použije se otočení přidruženého tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikované otočení navíc k tomu, že text samotný má také aplikované otočení. Výsledná hodnota vizuálního otáčení textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Přečtěte si float.
type: docs
weight: 235
url: /cs/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() metoda

Určuje vlastní otočení, které se používá na text v ohraničujícím rámečku. Pokud není určeno, použije se otočení přidruženého tvaru. Pokud je určeno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikované otočení navíc k tomu, že text samotný má také aplikované otočení. Výsledná hodnota vizuálního otočení textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Přečtěte si **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Poznámky

Zvažte případ, kdy má tvar otočení o 90 stupňů po směru hodinových ručiček. K tomu je tělu textu aplikováno otočení o -90 stupňů proti směru hodinových ručiček. Pak by výsledný tvar vypadal, že je otočen, ale text v něm by se jevil, jako kdyby vůbec nebyl otočen.

## Viz také

* Třída [IChartTextBlockFormat](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)