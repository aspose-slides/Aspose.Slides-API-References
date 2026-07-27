---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os dados de formatação de linha efetiva com a herança aplicada.
type: docs
weight: 417
url: /pt/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() método

Obtém os dados de formatação de linha efetiva com a herança aplicada.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### Valor de retorno

Um [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Observações

Este exemplo demonstra como obter as propriedades de formatação de linha efetiva da forma. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Classe [LineFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)