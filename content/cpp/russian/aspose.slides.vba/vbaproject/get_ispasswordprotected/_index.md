---
title: get_IsPasswordProtected()
second_title: Aspose.Slides для C++ справочник API
description: Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. Только для чтения bool.
type: docs
weight: 40
url: /ru/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() метод

Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. Только для чтения **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## См. также

* Класс [VbaProject](../)
* Пространство имён [Aspose::Slides::Vba](../../)
* Библиотека [Aspose.Slides](../../../)