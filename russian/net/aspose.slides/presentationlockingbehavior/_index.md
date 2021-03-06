---
title: PresentationLockingBehavior
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет поведение в отношении обработкиIPresentation./ipresentation источник файл или Stream  при загрузке и работе с экземпляромIPresentation./ipresentationИсточник  это параметр передаваемыйIPresentation./ipresentation конструктор. В приведенном ниже примере источником является файл pres.pptx
type: docs
weight: 8910
url: /ru/net/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumeration

Представляет поведение в отношении обработки[`IPresentation`](../ipresentation) источник (файл или Stream ) при загрузке и работе с экземпляром[`IPresentation`](../ipresentation)Источник — это параметр, передаваемый[`IPresentation`](../ipresentation) конструктор. В приведенном ниже примере источником является файл «pres.pptx»:

```csharp
LoadOptions loadOptions = new LoadOptions { 
  BlobManagementOptions = { PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked } };
using (IPresentation pres = new Presentation("pres.pptx", loadOptions)) { }
```

В этом примере источник (файл «pres.pptx») будет заблокирован на[`IPresentation`](../ipresentation) время жизни экземпляра, т.е. не может быть изменено или удалено другим процессом.

```csharp
public enum PresentationLockingBehavior
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| LoadAndRelease | `0` | Источник будет заблокирован только на время[`IPresentation`](../ipresentation) выполнение конструктора.  Если[`IsTemporaryFilesAllowed`](../iblobmanagementoptions/istemporaryfilesallowed) имеет значение false, все BLOB-объекты будут загружены в память. В противном случае могут использоваться другие средства, такие как временные файлы. Это поведение медленнее, чемKeepLocked , и если возможно передать право владения источником[`IPresentation`](../ipresentation) , рекомендуется использоватьKeepLocked . |
| KeepLocked | `1` | Источник будет заблокирован на все время жизни[`IPresentation`](../ipresentation) экземпляр, пока он не будет удален. [`IsTemporaryFilesAllowed`](../iblobmanagementoptions/istemporaryfilesallowed)Для использования этого поведения необходимо установить значение true, иначе будет выдано исключение. Это поведение рекомендуется, оно быстрее и потребляет меньше памяти, чемLoadAndRelease . |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
