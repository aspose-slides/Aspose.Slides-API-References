---
title: Shapes()
second_title: Referencia de API de Aspose.Slides para C++
description: Recopila todas las instancias de Shape en la Presentation.
type: docs
weight: 1
url: /es/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) método


Recopila todas las instancias de [Shape](../../../aspose.slides/shape/) en el [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para recopilar formas |

### Valor devuelto

Colección de todas las formas que contiene la presentación
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // si la forma es AutoShape, agrega un borde sólido negro
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```




## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Clase [Shape](../../../aspose.slides/shape/)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Clase [Collect](../)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)