---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides для C++ API Reference
description: "Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение времени жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) нельзя изменить в течение времени жизни экземпляра Presentation. Пример:"
type: docs
weight: 1
url: /ru/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() метод

Это свойство определяет, может ли экземпляр класса [Presentation](../../presentation/) быть владельцем источника - файла или потока в течение времени жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) нельзя изменить в течение времени жизни экземпляра [Presentation](../../presentation/). Пример:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Примечания

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Будет выброшено исключение IOException, потому что pres.pptx заблокирован на время жизни Presentation
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