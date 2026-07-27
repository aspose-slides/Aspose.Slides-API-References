---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los datos de formato del marco de texto efectivos con la herencia aplicada.
type: docs
weight: 391
url: /es/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() método


Obtiene los datos de formato del marco de texto efectivos con la herencia aplicada.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### Valor devuelto

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Observaciones



Este ejemplo muestra cómo obtener algunas de las propiedades de formato del marco de texto efectivas. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Clase [TextFrameFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)