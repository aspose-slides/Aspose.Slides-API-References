---
title: AddTextFrame()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona um novo TextFrame a uma forma. Se a forma já possui TextFrame, então simplesmente altera seu texto.
type: docs
weight: 66
url: /pt/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) método


Adiciona um novo [TextFrame](../../textframe/) a uma forma. Se a forma já possui [TextFrame](../../textframe/) então simplesmente altera seu texto.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto padrão para um novo [TextFrame](../../textframe/). |
## Observações



O código de exemplo a seguir mostra como adicionar texto de marca d'água no PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 O exemplo a seguir mostra como criar uma Caixa de Texto em [Slide](../../slide/). 
```cpp
// Instancia a apresentação
auto pres = System::MakeObject<Presentation>();

// Obtém o primeiro slide na apresentação
auto slide = pres->get_Slides()->idx_get(0);
// Adiciona um AutoShape com o tipo definido como Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Adiciona TextFrame ao Rectangle
shape->AddTextFrame(u" ");
// Acessa o TextFrame
auto txtFrame = shape->get_TextFrame();
// Cria o objeto Paragraph para o TextFrame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Cria um objeto Portion para o parágrafo
auto portion = para->get_Portions()->idx_get(0);
// Define o texto
portion->set_Text(u"Aspose TextBox");
// Salva a apresentação no disco
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como adicionar coluna em Caixa de Texto. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Obtém o primeiro slide da apresentação
auto slide = presentation->get_Slides()->idx_get(0);
// Adiciona um AutoShape com o tipo definido como Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Adiciona TextFrame ao Rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Obtém o formato de texto do TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Especifica o número de colunas no TextFrame
format->set_ColumnCount(3);
// Especifica o espaçamento entre colunas
format->set_ColumnSpacing(10);
// Salva a apresentação
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../itextframe/)
* Classe [String](../../../system/string/)
* Classe [AutoShape](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)