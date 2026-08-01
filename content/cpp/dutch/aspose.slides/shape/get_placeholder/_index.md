---
title: get_Placeholder()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen IPlaceholder.
type: docs
weight: 14
url: /nl/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() methode

Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Opmerkingen

Het volgende voorbeeld toont hoe u Text wijzigt in [Placeholder](../../placeholder/). 
```cpp
// Instantieert een Presentation klasse
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Toegang tot de eerste dia
auto slide = pres->get_Slides()->idx_get(0);

// Itereert door shapes om de placeholder te vinden
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Wijzigt de tekst in elke placeholder
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Slaat de presentatie op schijf
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 Het volgende voorbeeld toont hoe u Prompt Text instelt in [Placeholder](../../placeholder/). 
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPlaceholder](../../iplaceholder/)
* Klasse [Shape](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)