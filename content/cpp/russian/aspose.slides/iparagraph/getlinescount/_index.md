---
title: GetLinesCount()
second_title: Справочник API Aspose.Slides для C++
description: Получить количество строк в абзаце.
type: docs
weight: 105
url: /ru/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() метод

Получить количество строк в абзаце.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```

### Возвращаемое значение

Количество строк в абзаце
## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## См. также

* Класс [IParagraph](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)