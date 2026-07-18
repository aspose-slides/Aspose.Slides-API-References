---
title: set_WrapText()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αληθές εάν το κείμενο είναι αναδιπλωμένο στα περιθώρια του TextFrame. Γράψτε NullableBool.
type: docs
weight: 131
url: /el/aspose.slides/textframeformat/set_wraptext/
---
## TextFrameFormat::set_WrapText(NullableBool) μέθοδος

**Αληθές** αν το κείμενο είναι αναδιπλωμένο στα περιθώρια του [TextFrame](../../textframe/). Γράψτε [NullableBool](../../nullablebool/).

```cpp
void Aspose::Slides::TextFrameFormat::set_WrapText(NullableBool value) override
```

## Παρατηρήσεις

Ο παρακάτω κώδικας δείγματος δείχνει πώς να αναδιπλώσετε το κείμενο στο [Presentation](../../presentation/).
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");
portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
auto textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_WrapText(NullableBool::True);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Απαρίθμηση [NullableBool](../../nullablebool/)
* Κλάση [TextFrameFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)