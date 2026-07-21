---
title: get_IsWriteProtected()
second_title: Aspose.Slides для C++ справочник API
description: Получает значение, указывающее, защищена ли привязанная презентация от записи.
type: docs
weight: 27
url: /ru/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() метод

Получает значение, указывающее, защищена ли привязанная презентация от записи.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```
## Примечания



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Если презентация защищена паролем для открытия, значение свойства равно NotDefined. 
## См. также

* Enum [NullableBool](../../nullablebool/)
* Класс [PresentationInfo](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)