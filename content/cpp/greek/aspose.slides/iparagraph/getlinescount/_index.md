---
title: GetLinesCount()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει τον αριθμό των γραμμών σε μια παράγραφο.
type: docs
weight: 105
url: /el/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() method


Λαμβάνει τον αριθμό των γραμμών σε μια παράγραφο.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```


### Τιμή Επιστροφής

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

* Κλάση [IParagraph](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)