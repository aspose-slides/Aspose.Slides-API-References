---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os dados de formatação de parágrafo efetivos com a herança aplicada.
type: docs
weight: 365
url: /pt/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() método


Obtém os dados de formatação de parágrafo efetivos com a herança aplicada.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Valor de retorno

Um [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Observações



Este exemplo demonstra a obtenção de algumas propriedades efetivas de formato de parágrafo. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Classe [ParagraphFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)