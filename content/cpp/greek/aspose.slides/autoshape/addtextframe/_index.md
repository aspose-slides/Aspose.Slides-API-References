---
title: AddTextFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει ένα νέο TextFrame σε ένα σχήμα. Εάν το σχήμα έχει ήδη TextFrame, τότε απλώς αλλάζει το κείμενό του.
type: docs
weight: 66
url: /el/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) μέθοδος

Προσθέτει ένα νέο [TextFrame](../../textframe/) σε ένα σχήμα. Εάν το σχήμα έχει ήδη [TextFrame](../../textframe/) τότε απλώς αλλάζει το κείμενό του.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Προεπιλεγμένο κείμενο για ένα νέο [TextFrame](../../textframe/). |
## Παρατηρήσεις

Ο παρακάτω κώδικας δείγματος δείχνει πώς να προσθέσετε κείμενο υδατογράφησης στο PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε πλαίσιο κειμένου στο [Slide](../../slide/).
```cpp
// Δημιουργεί παρουσίαση
auto pres = System::MakeObject<Presentation>();

// Λαμβάνει την πρώτη διαφάνεια στην παρουσίαση
auto slide = pres->get_Slides()->idx_get(0);
// Προσθέτει ένα AutoShape με τύπο Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Προσθέτει TextFrame στο Rectangle
shape->AddTextFrame(u" ");
// Προσπελαύνει το πλαίσιο κειμένου
auto txtFrame = shape->get_TextFrame();
// Δημιουργεί το αντικείμενο Paragraph για το πλαίσιο κειμένου
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Δημιουργεί ένα αντικείμενο Portion για την παράγραφο
auto portion = para->get_Portions()->idx_get(0);
// Ορίζει το κείμενο
portion->set_Text(u"Aspose TextBox");
// Αποθηκεύει την παρουσίαση στον δίσκο
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε στήλη σε πλαίσιο κειμένου.
```cpp
auto presentation = System::MakeObject<Presentation>();

// Λαμβάνει την πρώτη διαφάνεια στην παρουσίαση
auto slide = presentation->get_Slides()->idx_get(0);
// Προσθέτει AutoShape με τύπο Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Προσθέτει TextFrame στο Rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Λαμβάνει τη μορφή κειμένου του TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Ορίζει τον αριθμό των στηλών στο TextFrame
format->set_ColumnCount(3);
// Ορίζει το διάστημα μεταξύ των στηλών
format->set_ColumnSpacing(10);
// Αποθηκεύει την παρουσίαση
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ITextFrame](../../itextframe/)
* Κλάση [String](../../../system/string/)
* Κλάση [AutoShape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)