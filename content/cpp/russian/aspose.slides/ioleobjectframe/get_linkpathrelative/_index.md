---
title: get_LinkPathRelative()
second_title: Aspose.Slides для C++ справочник API
description: "Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. Только для чтения System::String."
type: docs
weight: 118
url: /ru/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() метод


Возвращает относительный путь к связанному файлу, если он присутствует, в противном случае возвращает пустую строку. Только для чтения [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Примечания


В презентациях Ppt некоторые ссылки на объекты Ole могут иметь относительное представление. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [IOleObjectFrame](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)