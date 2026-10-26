---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiva bakgrundsdata med ärftlighet tillämpad.
type: docs
weight: 118
url: /sv/aspose.slides/background/geteffective/
---
## Background::GetEffective() metod

Hämtar effektiva bakgrundsdata med ärftlighet tillämpad.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### Returvärde

Ett [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Anmärkningar

Detta exempel demonstrerar hur man får effektiva bakgrundsegenskaper.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Klass [Background](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)