---
title: get_Placeholder()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il segnaposto per una forma. Restituisce null se la forma non ha alcun segnaposto. Solo lettura IPlaceholder.
type: docs
weight: 14
url: /it/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() metodo


Restituisce il segnaposto per una forma. Restituisce null se la forma non ha alcun segnaposto. Solo lettura [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Osservazioni


Il seguente esempio mostra come modificare il Text in [Placeholder](../../placeholder/). 
```cpp
// Istanzia una classe Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Accede alla prima slide
auto slide = pres->get_Slides()->idx_get(0);

// Itera attraverso le forme per trovare il segnaposto
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Modifica il testo in ogni segnaposto
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Salva la presentazione su disco
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 Il seguente esempio mostra come impostare il Prompt Text in [Placeholder](../../placeholder/). 
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

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPlaceholder](../../iplaceholder/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)