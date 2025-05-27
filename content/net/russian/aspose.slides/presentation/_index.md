---
title: Презентация
second_title: Ссылка по API Aspose.Slides для .NET
description: Представляет собой презентацию Microsoft PowerPoint.
type: docs
weight: 9320
url: /ru/aspose.slides/presentation/
---

## Класс Presentation

Представляет собой презентацию Microsoft PowerPoint.

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

## Свойства

| Имя | Описание |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Возвращает все пользовательские части данных в презентации. Только для чтения [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Возвращает коллекцию всех встроенных аудиофайлов в презентации. Только для чтения [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Возвращает коллекцию авторов комментариев. Только для чтения [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Возвращает или устанавливает дату и время, которые заменят содержимое полей даты и времени. По умолчанию время создания этого объекта презентации. Чтение/запись DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Возвращает пользовательские данные презентации. Только для чтения [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Возвращает стиль текста по умолчанию для фигур. Только для чтения [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Возвращает коллекцию подписей, используемых для подписи презентации. Только для чтения [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Возвращает объект DocumentProperties, который содержит стандартные и пользовательские свойства документа. Только для чтения [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Представляет первый номер слайда в презентации |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Возвращает менеджер шрифтов. Только для чтения [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Возвращает актуальный менеджер заголовков и подвалов. Только для чтения [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Обеспечивает легкий доступ ко всем гиперссылкам, содержащимся на всех слайдах презентации (не на мастер-слайде, макетах, слайдах заметок). Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Возвращает коллекцию всех изображений в презентации. Только для чтения [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Возвращает список всех макетов слайдов, которые определены в презентации. Только для чтения [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Возвращает менеджер мастер-выдачи. Только для чтения [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Возвращает менеджер заметок. Только для чтения [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Возвращает список всех мастер-слайдов, которые определены в презентации. Только для чтения [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Возвращает мастер-тему. Только для чтения [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Возвращает объект размеров слайдов заметок. Только для чтения [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Получает менеджер разрешений для этой презентации. Только для чтения [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Возвращает список всех секций слайдов, которые определены в презентации. Только для чтения [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Возвращает список всех слайдов, которые определены в презентации. Только для чтения [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Возвращает настройки слайд-шоу для презентации. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Возвращает объект размера слайда. Только для чтения [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Возвращает информацию о том, из какого формата была загружена презентация. Только для чтения [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Получает или устанавливает проект VBA с макросами презентации. Чтение/запись [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Возвращает коллекцию всех встроенных видеозаписей в презентации. Только для чтения [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Получает свойства просмотра, применимые ко всей презентации. Только для чтения [`IViewProperties`](../iviewproperties). |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Освобождает все ресурсы, используемые этим объектом Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Возвращает объекты Image для всех слайдов презентации. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Возвращает объекты Thumbnail Image для указанных слайдов презентации. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Возвращает объекты Thumbnail Image для всех слайдов презентации с указанными размерами. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанными размерами. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Возвращает слайд, мастер-слайд или макетный слайд по Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Подсвечивает все совпадения регулярного выражения указанным цветом. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Подсвечивает все совпадения образца текста указанным цветом. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Подсвечивает все совпадения образца текста указанным цветом. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Объединяет фрагменты с одинаковым форматированием во всех абзацах во всех допустимых фигурах на всех слайдах. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Заменяет все совпадения регулярного выражения указанной строкой. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Сохраняет все слайды презентации в наборе файлов, представляющих разметку XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Сохраняет все слайды презентации в поток в указанном формате. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Сохраняет все слайды презентации в файл с указанным форматом. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Сохраняет все слайды презентации в поток в указанном формате с дополнительными опциями. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Сохраняет указанные слайды презентации в файл с указанным форматом с сохранением номеров страниц. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в файл с указанным форматом с сохранением номеров страниц. |

### Примеры

Следующий пример показывает, как создать презентацию PowerPoint.

```csharp
[C#]
// Создаем объект Presentation, представляющий файл презентации
using (Presentation presentation = new Presentation())
{
    // Получаем первый слайд
    ISlide slide = presentation.Slides[0];
    // Добавляем автофигуру типа линия
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Сохраняем файл презентации.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Следующий пример показывает, как открыть и сохранить презентацию.

```csharp
[C#]
// Загружаем любой поддерживаемый файл в Presentation, например, ppt, pptx, odp и т.д.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Сохраняем файл презентации.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IPresentation](../ipresentation)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->