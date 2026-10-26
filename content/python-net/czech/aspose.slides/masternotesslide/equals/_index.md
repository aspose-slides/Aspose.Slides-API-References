---
title: equals method
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/masternotesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Určuje, zda jsou dvě instance IBaseSlide rovnocenné.  
Vrácená hodnota je vypočtena na základě struktury snímku a statického obsahu.  
Dvě snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nebere v úvahu jedinečné hodnoty identifikátorů, např. SlideId, a dynamický obsah, např. aktuální hodnotu data v Date Placeholder.

### Návratová hodnota

**true** pokud je specifikovaný IBaseSlide roven aktuálnímu IBaseSlide;  
jinak **false** .


```python
def equals(self, slide):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide) | IBaseSlide, který se porovnává s aktuálním IBaseSlide. |

### Viz také
* class [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide)
* class [`MasterNotesSlide`](/slides/python-net/cs/aspose.slides/masternotesslide)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)