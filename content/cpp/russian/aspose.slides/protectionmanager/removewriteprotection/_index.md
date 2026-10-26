---
title: RemoveWriteProtection()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет защиту от записи для этой презентации.
type: docs
weight: 144
url: /ru/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() метод


Удаляет защиту от записи для этой презентации.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Примечания


Этот пример кода показывает, как удалить защиту от записи из PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Класс [ProtectionManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)