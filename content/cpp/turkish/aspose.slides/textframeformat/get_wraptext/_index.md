---
title: get_WrapText()
second_title: Aspose.Slides for C++ API Referansı
description: Metin, TextFrame'in kenar boşluklarında kaydırılmışsa True döner. NullableBool'ı okuyun.
type: docs
weight: 118
url: /tr/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() method

Metin [TextFrame](../../textframe/)'in kenar boşluklarında kaydırılıyorsa **True** olur. [NullableBool](../../nullablebool/)'i okuyun.

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## Açıklamalar

Aşağıdaki örnek kod, [Presentation](../../presentation/) içinde metni nasıl kaydıracağını gösterir. 
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

## Diğer Bağlantılar

* Enum [NullableBool](../../nullablebool/)
* Class [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)