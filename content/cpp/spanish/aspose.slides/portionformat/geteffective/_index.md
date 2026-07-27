---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los datos de formato de porción efectivos con la herencia aplicada.
type: docs
weight: 131
url: /es/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() método

Obtiene los datos de formato de porción efectivos con la herencia aplicada.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### Valor de retorno

A [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Comentarios

Este ejemplo muestra cómo obtener algunas propiedades de formato de porción efectivos. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Clase [PortionFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)