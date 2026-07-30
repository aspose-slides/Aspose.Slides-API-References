---
title: get_AutofitType()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la modalità di adattamento automatico del testo. Leggi TextAutofitType.
type: docs
weight: 222
url: /it/aspose.slides/textframeformat/get_autofittype/
---
## TextFrameFormat::get_AutofitType() metodo


Restituisce la modalità di adattamento automatico del testo. Leggi [TextAutofitType](../../textautofittype/).

```cpp
TextAutofitType Aspose::Slides::TextFrameFormat::get_AutofitType() override
```

## Osservazioni


Il seguente codice di esempio mostra come ridimensionare la forma per adattare il testo in un PowerPoint [Presentation](../../presentation/). 
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
Il seguente codice di esempio mostra come ridurre il testo in caso di overflow. 
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

## Vedi anche

* Enum [TextAutofitType](../../textautofittype/)
* Classe [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)