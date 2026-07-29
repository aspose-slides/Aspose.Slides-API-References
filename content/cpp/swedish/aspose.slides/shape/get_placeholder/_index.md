---
title: get_Placeholder()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar platshållaren för en form. Returnerar null om formen inte har någon platshållare. Skrivskyddad IPlaceholder.
type: docs
weight: 14
url: /sv/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() metod

Returnerar platshållaren för en form. Returnerar null om formen inte har någon platshållare. Skrivskyddad [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Anmärkningar

Följande exempel visar hur man ändrar Text i [Placeholder](../../placeholder/).
```cpp
// Instansierar en Presentation-klass
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Hämtar den första bilden
auto slide = pres->get_Slides()->idx_get(0);

// Itererar genom former för att hitta platshållaren
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Ändrar texten i varje platshållare
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Sparar presentationen till disk
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
Följande exempel visar hur man ställer in Prompt Text i [Placeholder](../../placeholder/).
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

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPlaceholder](../../iplaceholder/)
* Klass [Shape](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)