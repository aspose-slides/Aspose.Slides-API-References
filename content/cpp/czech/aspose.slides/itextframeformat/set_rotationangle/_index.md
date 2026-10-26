---
title: set_RotationAngle()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Specifikuje vlastní otočení, které se použije na text uvnitř ohraničovacího rámečku. Pokud není zadáno, použije se otočení přidruženého tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít aplikováno otočení navíc k otočení, které je aplikováno samotnému textu. Výsledná hodnota vizuálního otočení textu je souhrnem této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Write float.
type: docs
weight: 352
url: /cs/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) metoda

Specifikuje vlastní otočení, které se použije na text uvnitř ohraničujícího rámečku. Pokud není zadáno, použije se otočení přidruženého tvaru. Pokud je zadáno, pak se použije nezávisle na tvaru. To znamená, že tvar může mít aplikováno otočení navíc k otočení, které je aplikováno samotnému textu. Výsledná hodnota vizuálního otočení textu je souhrnem této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Write **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Poznámky

Zvažte situaci, kdy má tvar otočení o 90 stupňů po směru hodinových ručiček. K tomu se navíc tělu textu aplikuje otočení o -90 stupňů proti směru hodinových ručiček. Výsledný tvar se pak jeví jako otočený, ale text uvnitř něj vypadá, jako kdyby nebyl vůbec otočen.

## Viz také

* Třída [ITextFrameFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)