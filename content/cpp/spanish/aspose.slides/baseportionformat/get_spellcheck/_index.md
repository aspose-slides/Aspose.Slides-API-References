---
title: get_SpellCheck()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es false.
type: docs
weight: 599
url: /es/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() método

Obtiene un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Observaciones

El siguiente ejemplo muestra cómo habilitar la bandera SpellCheck antes de guardar la presentación: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Acceder a la primera porción de texto dentro de la primera forma en la primera diapositiva
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Habilitar la corrección ortográfica para esta porción de texto
portion->get_PortionFormat()->set_SpellCheck(true);
// Guardar la presentación modificada
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [BasePortionFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)