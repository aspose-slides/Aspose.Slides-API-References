---
title: equals method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
Určuje, zda jsou dvě instance IBaseSlide rovny.
            Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu.
            Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nebere v úvahu jedinečné identifikátory, např. SlideId, ani dynamický obsah, např. aktuální datum v Date Placeholder.

### Návratová hodnota

**true**  pokud je zadaná IBaseSlide rovna aktuální IBaseSlide; 
            jinak **false** .

```python
def equals(self, slide):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide) | IBaseSlide, se kterou se porovnává aktuální IBaseSlide. |

### Viz také
* třída [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide)
* třída [`MasterSlide`](/slides/python-net/cs/aspose.slides/masterslide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)