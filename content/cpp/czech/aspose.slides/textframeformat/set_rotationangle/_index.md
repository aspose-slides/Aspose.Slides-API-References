---
title: set_RotationAngle()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. Pokud není zadáno, použije se otočení odpovídajícího tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikováno otočení navíc k otočení samotného textu. Výsledná hodnota vizuálního otočení textu je odvozená z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Zapište float.
type: docs
weight: 313
url: /cs/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) metoda


Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. Pokud není zadáno, použije se otočení odpovídajícího tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikováno otočení navíc k otočení samotného textu. Výsledná hodnota vizuálního otočení textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Zapište **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## Poznámky


Zvažte případ, kdy má tvar aplikováno otočení o 90 stupňů ve směru hodinových ručiček. K tomu je tělo textu také otočeno o -90 stupňů proti směru hodinových ručiček. Pak by výsledný tvar vypadal otočený, ale text v něm by se jevil, jako kdyby nebyl vůbec otočen.

## Viz také

* Třída [TextFrameFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)