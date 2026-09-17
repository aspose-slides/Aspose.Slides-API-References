---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior перечисление

Представляет поведение, касающееся обработки источника [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation) (файл или **io.RawIOBase**) при загрузке и работе с экземпляром [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation).

Тип PresentationLockingBehavior раскрывает следующие члены:

## Поля

| Поле | Описание |
| :- | :- |
| LOAD_AND_RELEASE | Источник будет заблокирован только на время выполнения конструктора [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation).<br/>            Если [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) установлено в false, все BLOB-ы <br/>            будут загружены в память. В противном случае могут быть использованы другие средства, например временные файлы. Это поведение медленнее, чем [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/ru/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), и если возможно передать <br/>            владение источником [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation), рекомендуется использовать [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/ru/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | Источник будет заблокирован на весь срок жизни экземпляра [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation), пока он <br/>            не будет уничтожен.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) должно быть установлено в true для использования <br/>            этого поведения, иначе будет выброшено исключение. Это поведение рекомендуется, оно быстрее и потребляет меньше памяти, чем [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/ru/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |

### Примечания

Источник — это параметр, передаваемый конструктору [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). В приведённом ниже примере источник — файл "pres.pptx":

Для этого примера источник ("pres.pptx" файл) будет заблокирован на весь срок жизни [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation) экземпляра, т.е. его нельзя изменить или удалить другим процессом.

### См. также
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)