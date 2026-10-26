---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiva styckeformateringsdata med ärftlighet tillämpad.
type: docs
weight: 365
url: /sv/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() metod

Hämtar effektiva styckeformateringsdata med ärftlighet tillämpad.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```

### Returvärde

En [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Anmärkningar



Detta exempel demonstrerar att hämta några effektiva egenskaper för styckeformat.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Klass [ParagraphFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)