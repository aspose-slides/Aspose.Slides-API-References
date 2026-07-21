---
title: CheckWriteProtection()
second_title: Aspose.Slides для C++ API Reference
description: Проверяет, правильный ли пароль для изменения защищённой от записи презентации.
type: docs
weight: 66
url: /ru/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) метод

Проверяет, правильный ли пароль для изменения защищённой от записи презентации.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Пароль для проверки. |

### Возвращаемое значение

True если презентация защищена от записи и пароль правильный. False в противном случае.

## Примечания

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Вы должны проверить свойство [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) перед вызовом этого метода.
1. Когда пароль равен null или пуст, этот метод возвращает false.

## См. также

* Класс [String](../../../system/string/)
* Класс [PresentationInfo](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)