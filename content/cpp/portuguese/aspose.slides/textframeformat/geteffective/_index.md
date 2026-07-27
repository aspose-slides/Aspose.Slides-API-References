---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os dados de formatação efetiva da caixa de texto com a herança aplicada.
type: docs
weight: 391
url: /pt/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() método

Obtém os dados de formatação efetiva da caixa de texto com a herança aplicada.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### Valor de Retorno

Um [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Observações

Este exemplo demonstra a obtenção de algumas propriedades de formatação efetiva da caixa de texto.
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Classe [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)