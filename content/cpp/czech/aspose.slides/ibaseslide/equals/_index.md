---
title: Equals()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje, zda jsou dvě instance IBaseSlide stejné. Vrácená hodnota je vypočtena na základě struktury snímku a statického obsahu. Dva snímky jsou stejné, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. stejné. Při porovnání se neberou v úvahu jedinečné identifikátory, např. SlideId, ani dynamický obsah, např. aktuální hodnota data v zástupném symbolu data.
type: docs
weight: 183
url: /cs/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metoda

Určuje, zda jsou dvě instance [IBaseSlide](../) stejné. Vrácená hodnota je vypočtena na základě struktury snímku a statického obsahu. Dva snímky jsou stejné, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. stejné. Při porovnání se nebere v úvahu jedinečné identifikátory, např. SlideId, ani dynamický obsah, např. aktuální datum v Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | [IBaseSlide](../) k porovnání s aktuálním [IBaseSlide](../). |

### Návratová hodnota

**true** pokud je zadaný [IBaseSlide](../) roven aktuálnímu [IBaseSlide](../); jinak **false**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IBaseSlide](../)
* Obor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)