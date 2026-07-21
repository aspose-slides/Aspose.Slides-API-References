---
title: PresentationLockingBehavior
second_title: Справочник API Aspose.Slides для C++
description: "Представляет поведение, определяющее обращение с источником IPresentation (файл или System::IO::Stream) при загрузке и работе с экземпляром IPresentation."
type: docs
weight: 6748
url: /ru/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Представляет поведение, определяющее обращение с источником [IPresentation](../ipresentation/) (файл или [System::IO::Stream](../../system.io/stream/)) при загрузке и работе с экземпляром [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| LoadAndRelease | 0 | Источник будет заблокирован только на время выполнения конструктора [IPresentation](../ipresentation/). |
| KeepLocked | 1 | Источник будет заблокирован на весь срок жизни экземпляра [IPresentation](../ipresentation/), пока он не будет освобождён. |

## Примечания

Источник — это параметр, передаваемый в конструктор [IPresentation](../ipresentation/). В примере ниже источник — файл "pres.pptx": 

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

Для этого примера источник (файл "pres.pptx") будет заблокирован на время жизни экземпляра [IPresentation](../ipresentation/), т.е. не может быть изменён или удалён другим процессом. 

## См. также

* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)