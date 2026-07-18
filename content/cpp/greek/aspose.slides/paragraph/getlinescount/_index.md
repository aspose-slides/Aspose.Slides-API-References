---
title: GetLinesCount()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λάβετε τον αριθμό των γραμμών σε μια παράγραφο.
type: docs
weight: 118
url: /el/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() μέθοδος

Λάβετε τον αριθμό των γραμμών σε μια παράγραφο.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```

### Τιμή επιστροφής

Αριθμός γραμμών σε μια παράγραφο
## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## Δείτε επίσης

* Κλάση [Paragraph](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)