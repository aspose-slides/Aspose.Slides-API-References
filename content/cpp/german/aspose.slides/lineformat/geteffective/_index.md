---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt effektive Linienformatierungsdaten, wobei die Vererbung angewendet wird.
type: docs
weight: 417
url: /de/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() Methode


Ermittelt effektive Linienformatierungsdaten, wobei die Vererbung angewendet wird.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### Rückgabewert

Ein [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Anmerkungen



Dieses Beispiel zeigt, wie man die effektiven Linieneigenschaften einer Form abruft. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Klasse [LineFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)