---
title: get_IsWriteProtected()
second_title: Aspose.Slides для C++ Справочник API
description: Возвращает значение, указывающее, защищена ли связанная презентация от записи.
type: docs
weight: 27
url: /ru/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPPresentationInfo::get_IsWriteProtected() метод


Возвращает значение, указывающее, защищена ли связанная презентация от записи.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Примечания



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Если презентация защищена паролем для открытия, значение свойства равно NotDefined. Смотрите перечисление [NullableBool](../../nullablebool/). 
## Смотрите также

* Enum [NullableBool](../../nullablebool/)
* Класс [IPresentationInfo](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)