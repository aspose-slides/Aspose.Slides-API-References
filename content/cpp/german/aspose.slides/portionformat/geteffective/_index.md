---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Liefert die wirksamen Portion-Formatierungsdaten mit angewandter Vererbung.
type: docs
weight: 131
url: /de/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() Methode


Liefert die wirksamen Portion-Formatierungsdaten mit angewendeter Vererbung.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Rückgabewert

Ein [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Anmerkungen



Dieses Beispiel demonstriert das Abrufen einiger wirksamer Portion-Format-Eigenschaften. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Klasse [PortionFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)