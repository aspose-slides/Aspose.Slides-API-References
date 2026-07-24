---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt effektive Hintergrunddaten mit angewandter Vererbung.
type: docs
weight: 118
url: /de/aspose.slides/background/geteffective/
---
## Background::GetEffective() Methode

Ermittelt effektive Hintergrunddaten mit angewandter Vererbung.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### Rückgabewert

A [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).

## Hinweise

Dieses Beispiel demonstriert das Abrufen effektiver Hintergrund-Eigenschaften. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Klasse [Background](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)