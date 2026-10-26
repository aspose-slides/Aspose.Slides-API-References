---
title: get_IsPasswordProtected()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает значение, указывающее, защищена ли привязанная презентация паролем для открытия.
type: docs
weight: 14
url: /ru/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() метод


Возвращает значение, указывающее, защищена ли привязанная презентация паролем для открытия.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Примечания



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Смотрите также

* Класс [PresentationInfo](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)