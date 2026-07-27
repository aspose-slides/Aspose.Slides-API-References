---
title: GetEffective()
second_title: Referência de API do Aspose.Slides para C++
description: Obtém os dados de formatação de porção efetiva com a herança aplicada.
type: docs
weight: 131
url: /pt/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() método


Obtém os dados de formatação de porção efetiva com a herança aplicada.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Valor de Retorno

Um [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Observações



Este exemplo demonstra como obter algumas propriedades de formato de porção efetiva. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Classe [PortionFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)