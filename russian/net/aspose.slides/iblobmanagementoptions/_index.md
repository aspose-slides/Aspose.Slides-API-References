---
title: IBlobManagementOptions
second_title: Справочник по API Aspose.Slides для .NET
description: Большой двоичный объект BLOB  это двоичные данные хранящиеся как единое целое т. е. BLOB может быть аудио видео или самой презентацией . Для оптимизации потребления памяти при работе с BLOB-объектами используется ряд методов которые уже были сохранены в презентации или будут добавлены позже программно. ИспользуяIBlobManagementOptions./iblobmanagementoptionsвы можете изменить различные аспекты поведения в отношении больших двоичных объектов обработка дляIPresentation./ipresentationвремя жизни экземпляра.
type: docs
weight: 4890
url: /ru/net/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions interface

Большой двоичный объект (BLOB) — это двоичные данные, хранящиеся как единое целое, т. е. BLOB может быть аудио, видео или самой презентацией . Для оптимизации потребления памяти при работе с BLOB-объектами используется ряд методов, которые уже были сохранены в презентации или будут добавлены позже программно. Используя[`IBlobManagementOptions`](../iblobmanagementoptions)вы можете изменить различные аспекты поведения в отношении больших двоичных объектов обработка для[`IPresentation`](../ipresentation)время жизни экземпляра.

```csharp
public interface IBlobManagementOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [IsTemporaryFilesAllowed](../../aspose.slides/iblobmanagementoptions/istemporaryfilesallowed) { get; set; } | Это свойство определяет, можно ли создавать временные файлы при работе с BLOB, что значительно снижает потребление памяти, но требует прав для создания файлов.  Все файлы будут удалены после завершения работы с презентацией. |
| [MaxBlobsBytesInMemory](../../aspose.slides/iblobmanagementoptions/maxblobsbytesinmemory) { get; set; } | Определяет максимальный объем (в байтах), который могут занимать в памяти все BLOB-объекты. Во-первых, все BLOB-объекты загружаются в память как поведение по умолчанию, и только когда он достигает предела, определяемого этим свойством, могут быть задействованы другие механизмы (например, временные файлы). С точки зрения производительности наиболее эффективным способом является хранение BLOB в памяти, но с другой стороны, это приводит к высокому потреблению памяти, что может быть нежелательно. Используя это свойство, вы можете установить оптимальное поведение для вашей среды или другие требования.  Это свойство будет игнорироваться, если[`IsTemporaryFilesAllowed`](./istemporaryfilesallowed)равно установлено значение false. Нет смысла ограничивать максимальное количество BLOB в памяти, потому что если для [`IsTemporaryFilesAllowed`](./istemporaryfilesallowed)задано значение false, память - единственное место где можно хранить BLOB.  Значение по умолчанию:629 145 600 байт (600 Мб). |
| [PresentationLockingBehavior](../../aspose.slides/iblobmanagementoptions/presentationlockingbehavior) { get; set; } | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем исходного файла или потока в течение жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с большими двоичными объектами, но источник (поток или файл) нельзя изменить в течение времени существования экземпляра Presentation. Это пример: |
| [TempFilesRootPath](../../aspose.slides/iblobmanagementoptions/tempfilesrootpath) { get; set; } | Корневой путь, по которому будут создаваться временные файлы. Хостинг-процесс должен иметь права создавать там файлы и папки. |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->