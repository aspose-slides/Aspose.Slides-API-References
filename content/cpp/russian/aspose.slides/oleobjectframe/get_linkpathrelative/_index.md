---
title: get_LinkPathRelative()
second_title: Aspose.Slides для C++ API справка
description: "Возвращает относительный путь к связанному файлу, если он присутствует, в противном случае возвращает пустую строку. Только для чтения System::String."
type: docs
weight: 131
url: /ru/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() method


Возвращает относительный путь к связанному файлу, если он присутствует, в противном случае возвращает пустую строку. Только для чтения [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Примечания


В презентациях Ppt некоторые ссылки Ole-объектов могут иметь относительное представление. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## См. также

* Класс [String](../../../system/string/)
* Класс [OleObjectFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)