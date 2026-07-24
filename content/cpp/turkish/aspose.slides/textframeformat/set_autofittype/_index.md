---
title: set_AutofitType()
second_title: Aspose.Slides C++ API Referansı
description: Metnin otomatik sığdırma modunu ayarlar. TextAutofitType yazın.
type: docs
weight: 235
url: /tr/aspose.slides/textframeformat/set_autofittype/
---
## TextFrameFormat::set_AutofitType(TextAutofitType) metodu


Metnin otomatik sığdırma modunu ayarlar. [TextAutofitType](../../textautofittype/) yazın.

```cpp
void Aspose::Slides::TextFrameFormat::set_AutofitType(TextAutofitType value) override
```

## Açıklamalar


PowerPoint [Presentation](../../presentation/) içinde şekli Metne Sığdırmak için yeniden boyutlandırmayı gösteren aşağıdaki örnek kod. 
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
Taşma durumunda metni küçültmeyi gösteren aşağıdaki örnek kod. 
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

## Ayrıca Bakınız

* Enum [TextAutofitType](../../textautofittype/)
* Sınıf [TextFrameFormat](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)