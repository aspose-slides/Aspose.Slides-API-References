---
title: IPresentation
second_title: Aspose.Slides для .NET API Справочник
description: Презентационный документ
type: docs
weight: 6550
url: /ru/aspose.slides/ipresentation/
---

## Интерфейс IPresentation

Презентационный документ

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Свойства

| Название | Описание |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Возвращает все пользовательские части данных в презентации. Только для чтения [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Возвращает интерфейс IDisposable. Только для чтения IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Возвращает коллекцию всех вложенных аудиофайлов в презентации. Только для чтения [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Возвращает коллекцию авторов комментариев. Только для чтения [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Возвращает или устанавливает дату и время, которые будут подставлены в поля даты и времени. Время создания объекта Presentation по умолчанию. Чтение/запись DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Возвращает пользовательские данные презентации. Только для чтения [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Возвращает стиль текста по умолчанию для фигур. Только для чтения [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Возвращает коллекцию подписей, используемых для подписания презентации. Только для чтения [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Возвращает объект DocumentProperties, который содержит стандартные и пользовательские свойства документа. Только для чтения [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Представляет номер первого слайда в презентации. Чтение/запись Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Возвращает менеджер шрифтов. Только для чтения [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Возвращает менеджер заголовков и нижних колонтитулов презентации. Только для чтения [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Обеспечивает удобный доступ ко всем гиперссылкам, содержащимся во всех слайдах презентации (не в главном, макете, слайдах заметок). Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Возвращает коллекцию всех изображений в презентации. Только для чтения [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Возвращает список всех слайдов макета, определенных в презентации. Только для чтения [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Возвращает менеджер основного раздаточного слайда. Только для чтения [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Возвращает менеджер главных заметок слайда. Только для чтения [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Возвращает список всех главных слайдов, определенных в презентации. Только для чтения [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Возвращает главную тему презентации. Только для чтения [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Возвращает объект размера слайда заметок. Только для чтения [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Получает менеджера разрешений для этой презентации. Только для чтения [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Возвращает список всех секций слайдов, определенных в презентации. Только для чтения [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Возвращает список всех слайдов, определенных в презентации. Только для чтения [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Возвращает объект размера слайда. Только для чтения [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Возвращает информацию о том, из какого формата была загружена презентация. Только для чтения [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Получает проект VBA с макросами презентации. Чтение/запись [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Возвращает коллекцию всех встроенных видеофайлов в презентации. Только для чтения [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Получает общие свойства представления презентации. Только для чтения [`IViewProperties`](../iviewproperties). |

## Методы

| Название | Описание |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Возвращает объекты изображения миниатюры для всех слайдов презентации. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Возвращает объекты Bitmap миниатюры для указанных слайдов презентации. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Возвращает объекты изображения миниатюры для всех слайдов презентации с указанным размером. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Возвращает объекты изображения миниатюры для всех слайдов презентации с пользовательским масштабированием. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Возвращает объекты изображения миниатюры для указанных слайдов презентации с указанным размером. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Возвращает объекты изображения миниатюры для указанных слайдов презентации с пользовательским масштабированием. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Возвращает слайд, слайд-мастер или слайд-макет по идентификатору. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Подсвечивает все совпадения регулярного выражения заданным цветом. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Подсвечивает все совпадения образца текста заданным цветом. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Подсвечивает все совпадения образца текста заданным цветом. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Объединяет части с одинаковым форматированием во всех абзацах всех допустимых фигур во всех слайдах. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Заменяет все совпадения регулярного выражения заданной строкой. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Сохраняет все слайды презентации в набор файлов, представляющих XAML разметку. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Сохраняет все слайды презентации в поток в указанном формате. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Сохраняет все слайды презентации в файл с указанным форматом. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Сохраняет указанные слайды презентации в поток в указанном формате. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Сохраняет все слайды презентации в поток в указанном формате с дополнительными параметрами. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Сохраняет указанные слайды презентации в файл с указанным форматом. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Сохраняет все слайды презентации в файл с указанным форматом и дополнительными параметрами. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в поток в указанном формате. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в файл с указанным форматом. |

### Смотрите Также

* интерфейс [IPresentationComponent](../ipresentationcomponent)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->