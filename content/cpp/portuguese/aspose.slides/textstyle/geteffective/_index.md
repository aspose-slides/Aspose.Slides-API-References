---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os dados de formatação de estilo de texto efetivo com a herança aplicada.
type: docs
weight: 27
url: /pt/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() método


Obtém os dados de formatação de estilo de texto efetivo com a herança aplicada.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Valor de Retorno

Um [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Observações



Este exemplo demonstra como obter algumas propriedades de estilo de texto efetivo. 
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

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Classe [TextStyle](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)