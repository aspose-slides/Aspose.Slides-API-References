---
title: set_SpellCheck()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las comprobaciones ortográficas de los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es false.
type: docs
weight: 612
url: /es/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) método


Establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las comprobaciones ortográficas de los elementos de texto. Cuando se establece en true, la corrección ortográfica está permitida. El valor predeterminado es **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
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

## Ver también

* Clase [IBasePortionFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)