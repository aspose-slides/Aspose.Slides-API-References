---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Liefert die wirksamen Textstil-Formatierungsdaten mit angewandter Vererbung.
type: docs
weight: 27
url: /de/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() Methode


Liefert die wirksamen Textstil-Formatierungsdaten mit angewandter Vererbung.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Rückgabewert

Ein [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Bemerkungen



Dieses Beispiel demonstriert das Abrufen einiger wirksamer Textstil-Eigenschaften. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Klasse [TextStyle](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)