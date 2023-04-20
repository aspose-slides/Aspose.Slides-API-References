---
title: get_Placeholder()
second_title: Aspose.Slides for C++ API Reference
description: Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only IPlaceholder.
type: docs
weight: 14
url: /cpp/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() method


Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Remarks


The following example shows how to change Text in [Placeholder](../../placeholder/). 
```cpp
// Instantiates a Presentation class
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Accesses the first slide
auto slide = pres->get_Slides()->idx_get(0);

// Iterates through shapes to find the placeholder
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Changes the text in each placeholder
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Saves the presentation to disk
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to set Prompt Text in [Placeholder](../../placeholder/). 
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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPlaceholder](../../iplaceholder/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)