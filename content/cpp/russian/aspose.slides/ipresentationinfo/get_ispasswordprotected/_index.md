---
title: get_IsPasswordProtected()
second_title: Aspose.Slides для C++: справочник API
description: Получает значение, указывающее, защищена ли привязанная презентация паролем для открытия.
type: docs
weight: 14
url: /ru/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() метод


Получает значение, указывающее, защищена ли привязанная презентация паролем для открытия.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Примечания



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## См. также

* Класс [IPresentationInfo](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)