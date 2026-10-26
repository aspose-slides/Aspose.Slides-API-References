---
title: GetEffective()
second_title: Aspose.Slides C++-hez API hivatkozás
description: Megkapja a hatékony szövegstílus formázási adatokat az öröklődés alkalmazásával.
type: docs
weight: 27
url: /hu/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() metódus

Megkapja a hatékony szövegstílus formázási adatokat az öröklődés alkalmazásával.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```

### Visszatérési érték

Egy [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Megjegyzések

Ez a példa bemutatja a hatásos szövegstílus tulajdonságainak egy részének lekérését.
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

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Osztály [TextStyle](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)