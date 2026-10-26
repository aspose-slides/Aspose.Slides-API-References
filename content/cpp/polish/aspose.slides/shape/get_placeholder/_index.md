---
title: get_Placeholder()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu IPlaceholder.
type: docs
weight: 14
url: /pl/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() metoda

Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Uwagi

Poniższy przykład pokazuje, jak zmienić tekst w [Placeholder](../../placeholder/). 
```cpp
// Tworzy obiekt klasy Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Uzyskuje dostęp do pierwszego slajdu
auto slide = pres->get_Slides()->idx_get(0);

// Iteruje po kształtach, aby znaleźć placeholder
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Zmienia tekst w każdym placeholderze
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Zapisuje prezentację na dysku
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 Poniższy przykład pokazuje, jak ustawić tekst podpowiedzi w [Placeholder](../../placeholder/). 
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

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IPlaceholder](../../iplaceholder/)
* Klasa [Shape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)