---
title: get_Alignment()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca wyrównanie tekstu w akapicie bez dziedziczenia. Przeczytaj TextAlignment.
type: docs
weight: 1
url: /pl/aspose.slides/paragraphformat/get_alignment/
---
## ParagraphFormat::get_Alignment() metoda

Zwraca wyrównanie tekstu w akapicie bez dziedziczenia. Przeczytaj [TextAlignment](../../textalignment/).

```cpp
TextAlignment Aspose::Slides::ParagraphFormat::get_Alignment() override
```

## Uwagi

Poniższy przykładowy kod pokazuje, jak wyrównać akapity tekstu w programie PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"ParagraphsAlignment.pptx");

// Accessing first slide
auto slide = pres->get_Slides()->idx_get(0);
// Accessing the first and second placeholder in the slide and typecasting it as AutoShape
System::SharedPtr<ITextFrame> tf1 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(0)))->get_TextFrame();
System::SharedPtr<ITextFrame> tf2 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(1)))->get_TextFrame();
// Change the text in both placeholders
tf1->set_Text(u"Center Align by Aspose");
tf2->set_Text(u"Center Align by Aspose");
// Getting the first paragraph of the placeholders
System::SharedPtr<IParagraph> para1 = tf1->get_Paragraphs()->idx_get(0);
System::SharedPtr<IParagraph> para2 = tf2->get_Paragraphs()->idx_get(0);
// Aligning the text paragraph to center
para1->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
para2->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
//Writing the presentation as a PPTX file
pres->Save(u"Centeralign_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Wyliczenie [TextAlignment](../../textalignment/)
* Klasa [ParagraphFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)