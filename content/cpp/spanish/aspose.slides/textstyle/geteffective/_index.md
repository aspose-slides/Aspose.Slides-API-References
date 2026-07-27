---
title: GetEffective()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene los datos de formato de estilo de texto efectivos con la herencia aplicada.
type: docs
weight: 27
url: /es/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() método


Obtiene los datos de formato de estilo de texto efectivos con la herencia aplicada.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Valor devuelto

Un [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Observaciones



Este ejemplo muestra cómo obtener algunas de las propiedades efectivas del estilo de texto. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Clase [TextStyle](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)