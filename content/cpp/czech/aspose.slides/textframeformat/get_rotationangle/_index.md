---
title: get_RotationAngle()
second_title: Aspose.Slides pro C++ API reference
description: Určuje vlastní rotaci, která se aplikuje na text uvnitř ohraničujícího rámce. Pokud není zadáno, použije se rotace přidruženého tvaru. Pokud je zadáno, pak se aplikuje nezávisle na tvaru. To znamená, že tvar může mít aplikovanou rotaci navíc k rotaci, kterou má aplikovanou samotný text. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Vrací float.
type: docs
weight: 300
url: /cs/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() metoda

Určuje vlastní rotaci, která se aplikuje na text uvnitř ohraničujícího rámce. Pokud není zadáno, použije se rotace přidruženého tvaru. Pokud je zadáno, pak je aplikováno nezávisle na tvaru. To znamená, že tvar může mít aplikovanou rotaci navíc k rotaci, kterou má aplikovanou samotný text. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Vrací **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Poznámky

Uvažujme případ, kdy má tvar aplikovanou rotaci 90 stupňů vpravo (ve směru hodinových ručiček). K tomu má samotné tělo textu aplikovanou rotaci -90 stupňů vlevo (proti směru hodinových ručiček). Pak by výsledný tvar vypadal, že je natočen, ale text uvnitř něj by se jevil, jako by vůbec nebyl natočen.

## Viz také

* Třída [TextFrameFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)