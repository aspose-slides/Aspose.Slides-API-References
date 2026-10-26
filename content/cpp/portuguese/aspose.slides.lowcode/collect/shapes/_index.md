---
title: Shapes()
second_title: Referência da API Aspose.Slides para C++
description: Coleta todas as instâncias de Shape na Presentation.
type: docs
weight: 1
url: /pt/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) método

Coleta todas as instâncias de [Shape](../../../aspose.slides/shape/) na [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para coletar formas |

### Valor de Retorno

Coleção de todas as formas que estão contidas na apresentação

## Observações

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // se a forma for AutoShape, adicione uma borda preta sólida
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [Shape](../../../aspose.slides/shape/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [Collect](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)