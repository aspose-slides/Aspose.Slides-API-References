---
title: CheckWriteProtection()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, правильный ли пароль для изменения защищённой от записи презентации.
type: docs
weight: 66
url: /ru/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) метод


Проверяет, правильный ли пароль для изменения защищенной от записи презентации.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Пароль для проверки. |

### Возвращаемое значение

True, если презентация защищена от записи и пароль корректен. False в противном случае.
## Примечания



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Вы должны проверить свойство [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) перед вызовом этого метода.
1. Когда password равен null или пустой, этот метод возвращает false.



## См. также

* Класс [String](../../../system/string/)
* Класс [IPresentationInfo](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)