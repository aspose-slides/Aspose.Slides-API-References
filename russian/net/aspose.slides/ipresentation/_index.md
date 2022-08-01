---
title: IPresentation
second_title: Справочник по API Aspose.Slides для .NET
description: Презентационный документ
type: docs
weight: 6190
url: /ru/net/aspose.slides/ipresentation/
---
## IPresentation interface

Презентационный документ

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Возвращает все пользовательские части данных в презентации. Только для чтения[`ICustomXmlPart`](../icustomxmlpart) []. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Возвращает интерфейс IDisposable. Только для чтенияIDisposable . |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения[`IPresentationComponent`](../ipresentationcomponent) . |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Возвращает коллекцию всех встроенных аудиофайлов в презентацию. Только для чтения[`IAudioCollection`](../iaudiocollection) . |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Возвращает коллекцию комментариев авторов. Только для чтения[`ICommentAuthorCollection`](../icommentauthorcollection) . |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Возвращает или устанавливает дату и время, которые заменят содержимое полей datetime. Время создания этого объекта Presentation по умолчанию. Чтение/записьDateTime . |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Возвращает пользовательские данные презентации. Только для чтения[`ICustomData`](../icustomdata) . |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Возвращает стиль текста по умолчанию для фигур. Только для чтения[`ITextStyle`](../itextstyle) . |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Возвращает набор подписей, использованных для подписания презентации. Только для чтения[`IDigitalSignatureCollection`](../idigitalsignaturecollection) . |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Возвращает объект DocumentProperties, который содержит стандартные и настраиваемые свойства документа. Только для чтения[`IDocumentProperties`](../idocumentproperties) . |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Представляет номер первого слайда в презентации. Чтение/записьInt32 . |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Возвращает диспетчер шрифтов. Только для чтения[`IFontsManager`](../ifontsmanager) . |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Возвращает менеджер HeaderFooter презентации. Только для чтения[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Обеспечивает легкий доступ ко всем гиперссылкам, содержащимся во всех слайдах презентации (кроме мастер-слайдов, макетов и слайдов с примечаниями). Только для чтения[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Возвращает коллекцию всех изображений в презентации. Только для чтения[`IImageCollection`](../iimagecollection) . |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Возвращает список всех слайдов макета, определенных в презентации. Только для чтения[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) . |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Возвращает главного менеджера раздаточных материалов. Только для чтения[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) . |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Возвращает главный менеджер заметок. Только для чтения[`IMasterNotesSlideManager`](../imasternotesslidemanager) . |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Возвращает список всех мастер-слайдов, определенных в презентации. Только для чтения[`IMasterSlideCollection`](../imasterslidecollection) . |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Возвращает основную тему презентации. Только для чтения[`IMasterTheme`](../../aspose.slides.theme/imastertheme) . |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Возвращает объект размера слайда заметок. Только для чтения[`INotesSize`](../inotessize) . |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Получает менеджер разрешений для этой презентации. Только для чтения[`IProtectionManager`](../iprotectionmanager) . |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Возвращает список всех разделов слайдов, определенных в презентации. Только для чтения[`ISectionCollection`](../isectioncollection) . |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Возвращает список всех слайдов, определенных в презентации. Только для чтения[`ISlideCollection`](../islidecollection) . |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Возвращает объект размера слайда. Только для чтения[`ISlideSize`](../islidesize) . |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Возвращает информацию о том, из какого формата была загружена презентация. Только для чтения[`SourceFormat`](./sourceformat) . |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Получает проект VBA с макросами презентации. Чтение/запись[`IVbaProject`](../../aspose.slides.vba/ivbaproject) . |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Возвращает коллекцию всех встроенных видеофайлов в презентацию. Только для чтения[`IVideoCollection`](../ivideocollection) . |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Получает свойства широкого представления презентации. Только для чтения[`IViewProperties`](../iviewproperties) . |

## Методы

| Имя | Описание |
| --- | --- |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Возвращает слайд, MasterSlide или LayoutSlide по идентификатору. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | Возвращает объекты Thumbnail Bitmap для всех слайдов презентации. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | Возвращает объекты Thumbnail Bitmap для указанных слайдов презентации. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | Возвращает объекты Thumbnail Bitmap для всех слайдов презентации с указанным размером. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | Возвращает объекты Thumbnail Bitmap для всех слайдов презентации с пользовательским масштабированием. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | Возвращает объекты Thumbnail Bitmap для указанных слайдов презентации с указанным размером. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | Возвращает объекты Thumbnail Bitmap для указанных слайдов презентации с пользовательским масштабированием. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Соединения выполняются с одинаковым форматированием во всех абзацах во всех допустимых формах на всех слайдах. |
| [Print](../../aspose.slides/ipresentation/print#print)() | Печать всей презентации на принтере по умолчанию. |
| [Print](../../aspose.slides/ipresentation/print#print_1)(PrinterSettings) | Печать презентации в соответствии с заданными настройками принтера, с использованием стандартного (без пользовательского интерфейса) контроллера печати. |
| [Print](../../aspose.slides/ipresentation/print#print_3)(string) | Печать всей презентации на указанный принтер, с использованием стандартного (без пользовательского интерфейса) контроллера печати. |
| [Print](../../aspose.slides/ipresentation/print#print_2)(PrinterSettings, string) | Печать документа в соответствии с указанными настройками принтера с использованием стандартного (без пользовательского интерфейса) контроллера печати и имени презентации. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Сохраняет все слайды презентации в поток в указанном формате. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Сохраняет все слайды презентации в файл указанного формата. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Сохраняет указанные слайды презентации в потоке в указанном формате. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Сохраняет все слайды презентации в поток в указанном формате и с дополнительными параметрами. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Сохраняет указанные слайды презентации в файл с указанным форматом. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Сохраняет все слайды презентации в файл указанного формата и с дополнительными параметрами. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в потоке в указанном формате. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в файл с указанным форматом. |

### Смотрите также

* interface [IPresentationComponent](../ipresentationcomponent)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
