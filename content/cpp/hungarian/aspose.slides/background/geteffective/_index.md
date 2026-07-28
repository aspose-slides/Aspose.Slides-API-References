---
title: GetEffective()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a hatékony háttéradatokat az öröklődés alkalmazásával.
type: docs
weight: 118
url: /hu/aspose.slides/background/geteffective/
---
## Background::GetEffective() metódus


A öröklődés alkalmazása után lekéri a hatékony háttéradatokat.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Visszatérési érték

A [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Megjegyzések



Ez a példa bemutatja a hatékony háttér tulajdonságok lekérését. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Osztály [Background](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)