---
title: GetLinesCount()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o número de linhas em um parágrafo.
type: docs
weight: 118
url: /pt/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() método

Obtém o número de linhas em um parágrafo.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```

### Valor de Retorno

Contagem de linhas em um parágrafo
## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## Veja Também

* Classe [Paragraph](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)