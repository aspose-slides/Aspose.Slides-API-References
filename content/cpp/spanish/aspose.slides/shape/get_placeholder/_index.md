---
title: get_Placeholder()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el marcador de posición de una forma. Devuelve null si la forma no tiene marcador de posición. Solo lectura IPlaceholder.
type: docs
weight: 14
url: /es/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() método

Devuelve el marcador de posición de una forma. Devuelve null si la forma no tiene marcador de posición. Solo lectura [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Observaciones

El siguiente ejemplo muestra cómo cambiar Text en [Placeholder](../../placeholder/).
```cpp
// Instancia una clase Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Accede a la primera diapositiva
auto slide = pres->get_Slides()->idx_get(0);

// Recorre las formas para encontrar el marcador de posición
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Cambia el texto en cada marcador de posición
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Guarda la presentación en disco
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
El siguiente ejemplo muestra cómo establecer Prompt Text en [Placeholder](../../placeholder/).
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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPlaceholder](../../iplaceholder/)
* Clase [Shape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)