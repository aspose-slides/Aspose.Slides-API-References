---
title: get_Placeholder()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το σύμβολο κράτησης για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει σύμβολο κράτησης. Μόνο για ανάγνωση IPlaceholder.
type: docs
weight: 14
url: /el/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() μέθοδος


Επιστρέφει το σύμβολο κράτησης για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει σύμβολο κράτησης. Μόνο για ανάγνωση [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Παρατηρήσεις


Το ακόλουθο παράδειγμα δείχνει πώς να αλλάξετε το κείμενο σε [Placeholder](../../placeholder/). 
```cpp
// Δημιουργεί μια κλάση Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Προσπελαύνει την πρώτη διαφάνεια
auto slide = pres->get_Slides()->idx_get(0);

// Διατρέχει τα σχήματα για να βρει το σύμβολο κράτησης
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Αλλάζει το κείμενο σε κάθε σύμβολο κράτησης
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Αποθηκεύει την παρουσίαση στον δίσκο
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 Το ακόλουθο παράδειγμα δείχνει πώς να ορίσετε το κείμενο προτροπής σε [Placeholder](../../placeholder/). 
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

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPlaceholder](../../iplaceholder/)
* Κλάση [Shape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)