---
title: GetLinesCount()
second_title: Riferimento API Aspose.Slides per C++
description: Ottieni il numero di linee in un paragrafo.
type: docs
weight: 105
url: /it/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() metodo

Ottiene il numero di linee in un paragrafo.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```

### Valore di ritorno

Conteggio delle linee in un paragrafo
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

* Classe [IParagraph](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)