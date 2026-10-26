---
title: get_Placeholder()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja az alakzat helykitöltőjét. Null értéket ad vissza, ha az alakzatnak nincs helykitöltője. Csak olvasható IPlaceholder.
type: docs
weight: 14
url: /hu/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() metódus

Visszaadja a helykitöltőt egy alakzatra. Null értéket ad vissza, ha az alakzaton nincs helykitöltő. Csak olvasható [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Megjegyzések

A következő példa bemutatja, hogyan változtatható a Text a [Placeholder](../../placeholder/)-ben.
```cpp
// Példányosít egy Presentation osztályt
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Eléri az első diát
auto slide = pres->get_Slides()->idx_get(0);

// Végigiterál a alakzatokon, hogy megtalálja a helykitöltőt
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Módosítja a szöveget minden helykitöltőben
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Mentés a prezentációt a lemezre
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 A következő példa bemutatja, hogyan állítható be a Prompt Text a [Placeholder](../../placeholder/)-ben.
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

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IPlaceholder](../../iplaceholder/)
* Osztály [Shape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)