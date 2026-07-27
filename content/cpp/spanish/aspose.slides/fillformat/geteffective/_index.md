---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los datos de formato de relleno efectivos con la herencia aplicada.
type: docs
weight: 105
url: /es/aspose.slides/fillformat/geteffective/
---
## FillFormat::GetEffective() método


Obtiene los datos de formato de relleno efectivos con la herencia aplicada.

```cpp
System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::FillFormat::GetEffective() override
```


### Valor de retorno

Un [IFillFormatEffectiveData](../../ifillformateffectivedata/).
## Observaciones



Este ejemplo muestra cómo obtener las propiedades de formato de relleno efectivos de la forma. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveFillFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_FillFormat()->GetEffective();

Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(effectiveFillFormat->get_FillType()));
switch (effectiveFillFormat->get_FillType())
{
    case FillType::Solid:
        Console::WriteLine(String(u"Fill color: ") + effectiveFillFormat->get_SolidFillColor());
        break;

    case FillType::Pattern:
        Console::WriteLine(String(u"Pattern style: ") + ObjectExt::ToString(effectiveFillFormat->get_PatternFormat()->get_PatternStyle()));
        Console::WriteLine(String(u"Fore color: ") + effectiveFillFormat->get_PatternFormat()->get_ForeColor());
        Console::WriteLine(String(u"Back color: ") + effectiveFillFormat->get_PatternFormat()->get_BackColor());
        break;

    case FillType::Gradient:
        Console::WriteLine(String(u"Gradient direction: ") + ObjectExt::ToString(effectiveFillFormat->get_GradientFormat()->get_GradientDirection()));
        Console::WriteLine(String(u"Gradient stops count: ") + effectiveFillFormat->get_GradientFormat()->get_GradientStops()->get_Count());
        break;

    case FillType::Picture:
        Console::WriteLine(String(u"Picture width: ") + effectiveFillFormat->get_PictureFillFormat()->get_Picture()->get_Image()->get_Width());
        Console::WriteLine(String(u"Picture height: ") + effectiveFillFormat->get_PictureFillFormat()->get_Picture()->get_Image()->get_Height());
        break;

    default:
        break;
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* Clase [FillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)