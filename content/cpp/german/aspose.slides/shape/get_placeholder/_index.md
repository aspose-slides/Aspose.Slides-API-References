---
title: get_Placeholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar IPlaceholder.
type: docs
weight: 14
url: /de/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() Methode

Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Hinweise

Das folgende Beispiel zeigt, wie der Text in [Placeholder](../../placeholder/) geändert wird. 
```cpp
// Instanziiert eine Presentation-Klasse
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Greift auf die erste Folie zu
auto slide = pres->get_Slides()->idx_get(0);

// Iteriert über die Shapes, um den Platzhalter zu finden
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Ändert den Text in jedem Platzhalter
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Speichert die Präsentation auf die Festplatte
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 Das folgende Beispiel zeigt, wie der Prompt Text in [Placeholder](../../placeholder/) festgelegt wird. 
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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPlaceholder](../../iplaceholder/)
* Klasse [Shape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)