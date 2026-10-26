---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de effectieve achtergrondgegevens op met de toegepaste overerving.
type: docs
weight: 118
url: /nl/aspose.slides/background/geteffective/
---
## Background::GetEffective() methode


Haalt de effectieve achtergrondgegevens op met de toegepaste overerving.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Retourwaarde

Een [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Opmerkingen



Dit voorbeeld toont het verkrijgen van effectieve achtergrond-eigenschappen. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Klasse [Background](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)