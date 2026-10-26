---
title: get_AutofitType()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a szöveg automatikus illesztési módját. Olvassa el a TextAutofitType-ot.
type: docs
weight: 222
url: /hu/aspose.slides/textframeformat/get_autofittype/
---
## TextFrameFormat::get_AutofitType() metódus


Visszaadja a szöveg automatikus illesztési módját. Olvassa el [TextAutofitType](../../textautofittype/).

```cpp
TextAutofitType Aspose::Slides::TextFrameFormat::get_AutofitType() override
```

## Megjegyzések


Az alábbi minta kód bemutatja, hogyan lehet átméretezni az alakzatot a szöveghez illeszkedő módba egy PowerPoint [Presentation](../../presentation/)-ban. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");
portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
System::SharedPtr<ITextFrameFormat> textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_AutofitType(TextAutofitType::Shape);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```
Az alábbi minta kód bemutatja, hogyan lehet zsugorítani a szöveget túlcsordulás esetén. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");

portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
System::SharedPtr<ITextFrameFormat> textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_AutofitType(TextAutofitType::Normal);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```

## Lásd még

* Enum [TextAutofitType](../../textautofittype/)
* Osztály [TextFrameFormat](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)