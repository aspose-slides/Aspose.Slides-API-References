---
title: CheckWriteProtection()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, защищена ли презентация паролем от изменения.
type: docs
weight: 157
url: /ru/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) метод

Определяет, защищена ли презентация паролем от изменения.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Пароль для проверки. |

### Возвращаемое значение

True если пароль действителен; иначе — false.

## Примечания

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Перед вызовом этого метода следует проверить свойство [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/).
1. Когда пароль равен null или пустой строке, этот метод возвращает false.

## См. также

* Класс [String](../../../system/string/)
* Класс [IProtectionManager](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)