---
title: GetLinesCount()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottieni il numero di righe in un paragrafo.
type: docs
weight: 118
url: /it/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() metodo


Ottieni il numero di righe in un paragrafo.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```


### Valore di ritorno

Conteggio delle righe in un paragrafo
## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## Vedi anche

* Class [Paragraph](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)