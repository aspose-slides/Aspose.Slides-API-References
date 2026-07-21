---
title: set_DefaultTextLanguage()
second_title: Справочник API Aspose.Slides для C++
description: "Устанавливает язык по умолчанию для текста презентации. Укажите System::String."
type: docs
weight: 326
url: /ru/aspose.slides/iloadoptions/set_defaulttextlanguage/
---
## ILoadOptions::set_DefaultTextLanguage(System::String) метод

Устанавливает язык по умолчанию для текста презентации. Запишите [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DefaultTextLanguage(System::String value)=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DefaultTextLanguage(u"en-US");

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(loadOptions);

// Add new rectangle shape with text
System::SharedPtr<IAutoShape> shp = pres->get_Slide(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 50.0f, 50.0f, 150.0f, 50.0f);
shp->get_TextFrame()->set_Text(u"New Text");

// Check the first portion language
System::SharedPtr<IPortion> portion = shp->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
System::Console::WriteLine(portion->get_PortionFormat()->get_LanguageId());
```

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [ILoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)