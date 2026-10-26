---
title: get_Placeholder()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'espace réservé d'une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule IPlaceholder.
type: docs
weight: 14
url: /fr/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() méthode

Renvoie l'espace réservé d'une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Remarques

L'exemple suivant montre comment modifier Text dans [Placeholder](../../placeholder/).
```cpp
// Instancie une classe Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Accède à la première diapositive
auto slide = pres->get_Slides()->idx_get(0);

// Itère à travers les formes pour trouver l'espace réservé
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Modifie le texte dans chaque espace réservé
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Enregistre la présentation sur le disque
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
L'exemple suivant montre comment définir Prompt Text dans [Placeholder](../../placeholder/).
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

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPlaceholder](../../iplaceholder/)
* Classe [Shape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)