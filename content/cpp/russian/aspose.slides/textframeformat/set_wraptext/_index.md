---
title: set_WrapText()
second_title: Справочник API Aspose.Slides для C++
description: True если текст переносится по полям TextFrame. Запишите NullableBool.
type: docs
weight: 131
url: /ru/aspose.slides/textframeformat/set_wraptext/
---
## TextFrameFormat::set_WrapText(NullableBool) метод


**True** если текст переносится по полям [TextFrame](../../textframe/). Запишите [NullableBool](../../nullablebool/).

```cpp
void Aspose::Slides::TextFrameFormat::set_WrapText(NullableBool value) override
```

## Примечания


Следующий пример кода показывает, как перенести текст в [Presentation](../../presentation/). 
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

## См. также

* Перечисление [NullableBool](../../nullablebool/)
* Класс [TextFrameFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)