---
title: get_IsPasswordProtected()
second_title: Справочник API Aspose.Slides for C++
description: Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. Только для чтения bool.
type: docs
weight: 40
url: /ru/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() метод

Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. Только для чтения **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Класс [IVbaProject](../)
* Пространство имён [Aspose::Slides::Vba](../../)
* Библиотека [Aspose.Slides](../../../)