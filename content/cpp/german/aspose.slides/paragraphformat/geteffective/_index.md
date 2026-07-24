---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Liefert die wirksamen Absatzformatierungsdaten mit angewandter Vererbung.
type: docs
weight: 365
url: /de/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() Methode


Liefert die wirksamen Absatzformatierungsdaten mit angewandter Vererbung.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Rückgabewert

A [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Hinweise



Dieses Beispiel demonstriert das Abrufen einiger wirksamer Absatzformateigenschaften. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Klasse [ParagraphFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)