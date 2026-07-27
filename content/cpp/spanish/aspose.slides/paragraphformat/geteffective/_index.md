---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los datos de formato de párrafo efectivos con la herencia aplicada.
type: docs
weight: 365
url: /es/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() método


Obtiene los datos de formato de párrafo efectivos con la herencia aplicada.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Valor devuelto

A [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Observaciones



Este ejemplo muestra cómo obtener algunas propiedades de formato de párrafo efectivas. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Clase [ParagraphFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)