---
title: SetWriteProtection()
second_title: Aspose.Slides для C++ справочник API
description: Установить защиту от записи для этой презентации с указанным паролем.
type: docs
weight: 131
url: /ru/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) метод


Установить защиту от записи для этой презентации с указанным паролем.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Пароль. |
## Примечания



Следующий пример кода показывает, как установить защиту от записи для презентации. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [String](../../../system/string/)
* Класс [ProtectionManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)