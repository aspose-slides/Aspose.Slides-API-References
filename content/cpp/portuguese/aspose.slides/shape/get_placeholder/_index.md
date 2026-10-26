---
title: get_Placeholder()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o espaço reservado para uma forma. Retorna null se a forma não possuir um espaço reservado. Somente leitura IPlaceholder.
type: docs
weight: 14
url: /pt/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() método


Retorna o espaço reservado para uma forma. Retorna null se a forma não possuir um espaço reservado. Somente leitura [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Observações


O exemplo a seguir mostra como alterar o Texto em [Placeholder](../../placeholder/). 
```cpp
// Instancia a classe Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Accesses the first slide
auto slide = pres->get_Slides()->idx_get(0);

// Iterates through shapes to find the placeholder
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Altera o texto em cada placeholder
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Salva a apresentação no disco
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como definir o Texto de Prompt em [Placeholder](../../placeholder/). 
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPlaceholder](../../iplaceholder/)
* Classe [Shape](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)