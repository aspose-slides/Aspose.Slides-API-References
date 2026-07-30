---
title: AddTextFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge un nuovo TextFrame a una forma. Se la forma ha già un TextFrame, ne cambia semplicemente il testo.
type: docs
weight: 66
url: /it/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) metodo

Aggiunge un nuovo [TextFrame](../../textframe/) a una forma. Se la forma ha già [TextFrame](../../textframe/) allora semplicemente cambia il suo testo.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Testo predefinito per un nuovo [TextFrame](../../textframe/). |

## Osservazioni

Il codice di esempio seguente mostra come aggiungere testo filigrana in PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 L'esempio seguente mostra come creare una Text Box su [Slide](../../slide/). 
```cpp
// Istanzia la Presentazione
auto pres = System::MakeObject<Presentation>();

// Ottiene la prima diapositiva nella presentazione
auto slide = pres->get_Slides()->idx_get(0);
// Aggiunge un AutoShape con tipo impostato come Rettangolo
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Aggiunge TextFrame al Rettangolo
shape->AddTextFrame(u" ");
// Accede al frame di testo
auto txtFrame = shape->get_TextFrame();
// Crea l'oggetto Paragraph per il frame di testo
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Crea un oggetto Portion per il paragrafo
auto portion = para->get_Portions()->idx_get(0);
// Imposta il testo
portion->set_Text(u"Aspose TextBox");
// Salva la presentazione su disco
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 L'esempio seguente mostra come aggiungere una colonna in Text Box. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Ottiene la prima diapositiva nella presentazione
auto slide = presentation->get_Slides()->idx_get(0);
// Aggiunge un AutoShape con tipo impostato come Rettangolo
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Aggiunge TextFrame al Rettangolo
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Ottiene il formato del testo del TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Specifica il numero di colonne nel TextFrame
format->set_ColumnCount(3);
// Specifica la spaziatura tra le colonne
format->set_ColumnSpacing(10);
// Salva la presentazione
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../itextframe/)
* Classe [String](../../../system/string/)
* Classe [AutoShape](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)