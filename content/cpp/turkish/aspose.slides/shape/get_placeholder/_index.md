---
title: get_Placeholder()
second_title: Aspose.Slides için C++ API Referansı
description: Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt okunur IPlaceholder.
type: docs
weight: 14
url: /tr/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() method


Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt okunur [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Açıklamalar


Aşağıdaki örnek, [Placeholder](../../placeholder/) içinde Text nasıl değiştirileceğini gösterir. 
```cpp
// Bir Presentation sınıfı örnekler
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// İlk slayta erişir
auto slide = pres->get_Slides()->idx_get(0);

// Yer tutucuyu bulmak için şekillerde döner
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Her yer tutucudaki metni değiştirir
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Sunumu diske kaydeder
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 Aşağıdaki örnek, [Placeholder](../../placeholder/) içinde Prompt Text nasıl ayarlanacağını gösterir. 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation2.pptx");

auto slide = pres->get_Slides()->idx_get(0);
for (auto&& shape : slide->get_Slide()->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr && System::ObjectExt::Is<AutoShape>(shape))
    {
        System::String text = u"";
        if (shape->get_Placeholder()->get_Type() == PlaceholderType::CenteredTitle)
        {
            text = u"Add Title";
        }
        else if (shape->get_Placeholder()->get_Type() == PlaceholderType::Subtitle)
        {
            text = u"Add Subtitle";
        }

        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(text);

        System::Console::WriteLine(System::String::Format(u"Placeholder with text: {0}", text));
    }
}

pres->Save(u"Placeholders_PromptText.pptx", SaveFormat::Pptx);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPlaceholder](../../iplaceholder/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)