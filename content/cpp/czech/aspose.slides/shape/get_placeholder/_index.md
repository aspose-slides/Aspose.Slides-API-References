---
title: get_Placeholder()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací zástupný prvek pro shape. Vrací null, pokud shape nemá zástupný prvek. Pouze pro čtení IPlaceholder.
type: docs
weight: 14
url: /cs/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() metoda

Vrací zástupný prvek pro shape. Vrací null, pokud shape nemá zástupný prvek. Pouze pro čtení [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Poznámky

Následující příklad ukazuje, jak změnit Text v [Placeholder](../../placeholder/). 
```cpp
// Vytváří instanci třídy Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Přistupuje k prvnímu slidu
auto slide = pres->get_Slides()->idx_get(0);

// Prochází tvary, aby našel placeholder
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Mění text v každém placeholderu
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Uloží prezentaci na disk
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 Následující příklad ukazuje, jak nastavit Prompt Text v [Placeholder](../../placeholder/). 
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

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPlaceholder](../../iplaceholder/)
* Třída [Shape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)