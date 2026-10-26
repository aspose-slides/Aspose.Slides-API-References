---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides para Referência da API C++
description: Define hiperlink externo ao clicar.
type: docs
weight: 1
url: /pt/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) método

Define hiperlink externo ao clicar.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Observações

O código de exemplo a seguir mostra como adicionar uma Caixa de Texto com [Hyperlink](../../hyperlink/).
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Obtém o primeiro slide da apresentação
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Adiciona um objeto AutoShape com o tipo definido como Retângulo
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Acessa a propriedade ITextFrame associada ao AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Adiciona algum texto ao quadro
portion->set_Text(u"Aspose.Slides");

// Define o Hyperlink para o texto da porção
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Salva a apresentação PPTX
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHyperlink](../../ihyperlink/)
* Classe [String](../../../system/string/)
* Classe [HyperlinkManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)