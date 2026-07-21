---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides для C++ справочник API
description: "Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника - файла или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает уменьшить расход памяти и повысить производительность при работе с BLOB, но источник (поток или файл) нельзя изменить в течение срока жизни экземпляра Presentation. Это пример:"
type: docs
weight: 14
url: /ru/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) метод

Это свойство определяет, может ли экземпляр класса [Presentation](../../presentation/) быть владельцем источника - файла или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает снизить расход памяти и повысить производительность при работе с BLOBs, но источник (поток или файл) нельзя изменить в течение срока жизни экземпляра [Presentation](../../presentation/). Это пример:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Примечания

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException будет выброшено, потому что pres.pptx заблокирован на время жизни Presentation
    // File::Delete(u"pres.pptx");
}
// после уничтожения объекта Presentation файл разблокируется и может быть удалён
IO::File::Delete(u"pres.pptx");
```

## См. также

* Перечисление [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Класс [IBlobManagementOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)