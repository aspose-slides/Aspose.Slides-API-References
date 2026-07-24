---
title: get_AutofitType()
second_title: Aspose.Slides için C++ API Referansı
description: Metnin otomatik sığdırma modunu döndürür. TextAutofitType okuyun.
type: docs
weight: 222
url: /tr/aspose.slides/textframeformat/get_autofittype/
---
## TextFrameFormat::get_AutofitType() method


Metnin otomatik sığdırma modunu döndürür. [TextAutofitType](../../textautofittype/) okuyun.

```cpp
TextAutofitType Aspose::Slides::TextFrameFormat::get_AutofitType() override
```

## Açıklamalar


Aşağıdaki örnek kod, bir PowerPoint [Presentation](../../presentation/) içinde şekli Metne Sığdırmak için yeniden boyutlandırmanın nasıl yapılacağını gösterir. 
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
 Aşağıdaki örnek kod, taşma durumunda metni nasıl küçülteceğinizi gösterir. 
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
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)