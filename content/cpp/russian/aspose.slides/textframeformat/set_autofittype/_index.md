---
title: set_AutofitType()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает режим автоподгонки текста. Запишите TextAutofitType.
type: docs
weight: 235
url: /ru/aspose.slides/textframeformat/set_autofittype/
---
## TextFrameFormat::set_AutofitType(TextAutofitType) метод


Устанавливает режим автоподгонки текста. Запишите [TextAutofitType](../../textautofittype/).

```cpp
void Aspose::Slides::TextFrameFormat::set_AutofitType(TextAutofitType value) override
```

## Замечания


Следующий пример кода демонстрирует, как изменить размер фигуры, чтобы подогнать текст в PowerPoint [Presentation](../../presentation/). 
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
 Следующий пример кода демонстрирует, как уменьшить текст при переполнении. 
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

## См. также

* Перечисление [TextAutofitType](../../textautofittype/)
* Класс [TextFrameFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)