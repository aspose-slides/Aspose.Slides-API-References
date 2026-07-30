---
title: GetEffective()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá data efektivního formátování odstavce s aplikovaným děděním.
type: docs
weight: 365
url: /cs/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() metoda


Získá data efektivního formátování odstavce s aplikovaným děděním.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Návratová hodnota

Jedná se o [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).

## Poznámky



Tento příklad ukazuje získání některých vlastností efektivního formátu odstavce. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Class [ParagraphFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)