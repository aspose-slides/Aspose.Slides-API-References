---
title: get_SpellCheck()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es false.
type: docs
weight: 599
url: /es/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() método


Obtiene un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Observaciones


El siguiente ejemplo muestra cómo habilitar la bandera SpellCheck antes de guardar la presentación: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Véase también

* Clase [IBasePortionFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)