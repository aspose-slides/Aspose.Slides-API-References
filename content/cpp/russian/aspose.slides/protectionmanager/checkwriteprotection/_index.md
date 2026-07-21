---
title: CheckWriteProtection()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, защищена ли презентация паролем от изменения.
type: docs
weight: 157
url: /ru/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) метод

Определяет, является ли презентация защищённой паролем от изменения.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Пароль для проверки. |

### Возвращаемое значение

true, если пароль действителен; иначе — false.

## Примечания

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Перед вызовом этого метода следует проверить свойство [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/).
2. Если пароль имеет значение null или пуст, этот метод возвращает false.

## См. также

* Класс [String](../../../system/string/)
* Класс [ProtectionManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)