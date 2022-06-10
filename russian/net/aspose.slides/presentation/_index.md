---
title: Presentation
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет презентацию Microsoft PowerPoint.
type: docs
weight: 8870
url: /ru/net/aspose.slides/presentation/
---
## Presentation class

Представляет презентацию Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Presentation](presentation#constructor)() | Этот конструктор создает новую презентацию с нуля. Созданная презентация имеет один пустой слайд. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Этот конструктор создает новую презентацию с нуля. Созданная презентация имеет один пустой слайд. |
| [Presentation](presentation#constructor_2)(Stream) | Этот конструктор является основным механизмом для чтения существующей презентации. |
| [Presentation](presentation#constructor_4)(string) | Этот конструктор получает путь к исходному файлу, из которого считывается содержимое презентации. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Этот конструктор является основным механизмом для чтения существующей презентации. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Этот конструктор получает путь к исходному файлу, из которого считывается содержимое презентации. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Возвращает все пользовательские части данных в презентации. Только для чтения[`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Возвращает коллекцию всех встроенных аудиофайлов в презентации. Только чтение[`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Возвращает коллекцию авторов комментариев. Только для чтения[`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Возвращает или устанавливает дату и время, которые заменят содержимое полей даты и времени. Время создания этого объекта Presentation по умолчанию. Чтение/записьDateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Возвращает пользовательские данные презентации. Только для чтения[`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Возвращает стиль текста по умолчанию для фигур. Только для чтения[`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Возвращает набор подписей, использованных для подписания презентации. Только для чтения[`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Возвращает объект DocumentProperties, который содержит стандартные и пользовательские свойства документа. Только для чтения[`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Представляет номер первого слайда в презентации |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Возвращает диспетчер шрифтов. Только для чтения[`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Возвращает фактический менеджер HeaderFooter. Только для чтения[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Обеспечивает легкий доступ ко всем гиперссылкам, содержащимся во всех слайдах презентации (кроме мастер-слайдов, макетов, слайдов с примечаниями). Только для чтения[`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Возвращает коллекцию всех изображений в презентации. Только для чтения[`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Возвращает список всех слайдов макета, определенных в презентации. Только для чтения[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Возвращает главного менеджера раздаточных материалов. Только чтение[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Возвращает мастер-менеджер заметок. Только для чтения[`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Возвращает список всех мастер-слайдов, определенных в презентации. Только для чтения[`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Возвращает основную тему. Только для чтения[`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Возвращает объект размера слайда заметок. Только для чтения[`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Получает менеджер разрешений для этой презентации. Только для чтения[`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Возвращает список всех разделов слайдов, определенных в презентации. Только для чтения[`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Возвращает список всех слайдов, определенных в презентации. Только для чтения[`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Возвращает объект размера слайда. Только для чтения[`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Возвращает информацию о том, из какого формата была загружена презентация. Только для чтения[`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Получает или задает проект VBA с макросами презентации. Чтение/запись[`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Возвращает коллекцию всех встроенных видеофайлов в презентации. Только для чтения[`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Получает свойства широкого представления презентации. Только для чтения[`IViewProperties`](../iviewproperties). |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Освобождает все ресурсы, используемые этим объектом Presentation. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Возвращает слайд, MasterSlide или LayoutSlide по идентификатору. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | Возвращает объекты Thumbnail Bitmap для всех слайдов презентации. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | Возвращает объекты Thumbnail Bitmap для указанных слайдов презентации. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | Возвращает объекты Thumbnail Bitmap для всех слайдов презентации указанного размера. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | Возвращает объекты Thumbnail Bitmap для всех слайдов презентации с пользовательским масштабированием. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | Возвращает объекты Thumbnail Bitmap для указанных слайдов презентации с указанным размером. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | Возвращает объекты Thumbnail Bitmap для указанных слайдов презентации с пользовательским масштабированием. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Соединения выполняются с одинаковым форматированием во всех абзацах во всех допустимых формах на всех слайдах. |
| [Print](../../aspose.slides/presentation/print#print)() | Печать всей презентации на принтер по умолчанию. |
| [Print](../../aspose.slides/presentation/print#print_1)(PrinterSettings) | Печать презентации в соответствии с заданными настройками принтера, с использованием стандартного (без пользовательского интерфейса) контроллера печати. |
| [Print](../../aspose.slides/presentation/print#print_3)(string) | Печать всей презентации на указанный принтер, с использованием стандартного (без пользовательского интерфейса) контроллера печати. |
| [Print](../../aspose.slides/presentation/print#print_2)(PrinterSettings, string) | Печатает документ в соответствии с указанными настройками принтера, используя стандартный (без пользовательского интерфейса) контроллер печати и имя презентации. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Сохраняет все слайды презентации в поток в указанном формате. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Сохраняет все слайды презентации в файл указанного формата. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номера страницы. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Сохраняет все слайды презентации в поток в указанном формате и с дополнительными параметрами. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Сохраняет указанные слайды презентации в файл заданного формата с сохранением номера страницы. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) | Сохраняет все слайды презентации в файл заданного формата и с дополнительными параметрами. |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номера страницы. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в файл заданного формата с сохранением номера страницы. |

### Смотрите также

* interface [IPresentation](../ipresentation)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
