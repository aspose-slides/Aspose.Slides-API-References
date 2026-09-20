---
title: equals method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/slide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Určuje, zda jsou dva objekty typu IBaseSlide rovny.
            Vrácená hodnota je vypočítána na základě struktury snímku a statického obsahu.
            Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení. atd. rovny. Porovnání nebere v úvahu jedinečné hodnoty identifikátorů, např. SlideId a dynamický obsah, např. aktuální datum v zástupci data.

### Návratová hodnota

**true**  pokud je specifikovaný IBaseSlide roven aktuálnímu IBaseSlide; 
            jinak **false** .

```python
def equals(self, slide):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide) | IBaseSlide, se kterým se porovnává aktuální IBaseSlide. |

### Viz také
* třída [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide)
* třída [`Slide`](/slides/python-net/cs/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)