---
title: Presentation
second_title: Aspose.Sildes для .NET API Reference
description: Представляет презентацию Microsoft PowerPoint.
type: docs
weight: 9590
url: /ru/aspose.slides/presentation/
---
## Класс Presentation

Представляет презентацию Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Presentation](presentation#constructor)() | Этот конструктор создает новую презентацию с нуля. Созданная презентация содержит один пустой слайд. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Этот конструктор создает новую презентацию с нуля. Созданная презентация содержит один пустой слайд. |
| [Presentation](presentation#constructor_2)(Stream) | Этот конструктор является основным способом чтения существующей Presentation. |
| [Presentation](presentation#constructor_4)(string) | Этот конструктор принимает путь к исходному файлу, из которого читается содержимое Presentation. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Этот конструктор является основным способом чтения существующей Presentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Этот конструктор принимает путь к исходному файлу, из которого читается содержимое Presentation. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Возвращает все пользовательские части данных в презентации. Только для чтения [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Возвращает коллекцию всех встроенных аудиофайлов в презентации. Только для чтения [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Возвращает коллекцию авторов комментариев. Только для чтения [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Возвращает или задает дату и время, которые заменят содержимое полей datetime. По умолчанию — время создания этого объекта Presentation. Чтение/запись DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Возвращает пользовательские данные презентации. Только для чтения [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Возвращает стиль текста по умолчанию для фигур. Только для чтения [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Возвращает коллекцию подписей, используемых для подписи презентации. Только для чтения [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Возвращает объект DocumentProperties, содержащий стандартные и пользовательские свойства документа. Только для чтения [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Представляет номер первого слайда в презентации |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Возвращает менеджер шрифтов. Только для чтения [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Возвращает текущий менеджер HeaderFooter. Только для чтения [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Обеспечивает простой доступ ко всем гиперссылкам, содержащимся во всех слайдах презентации (не в шаблонах, оформлении, слайдах заметок). Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Возвращает коллекцию всех изображений в презентации. Только для чтения [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Возвращает список всех слайдов оформления, определенных в презентации. Только для чтения [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Возвращает менеджер шаблона раздаточного материала. Только для чтения [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Возвращает менеджер шаблона заметок. Только для чтения [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Возвращает список всех master-слайдов, определенных в презентации. Только для чтения [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Возвращает master-тему. Только для чтения [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Возвращает объект размера слайда заметок. Только для чтения [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Получает менеджер разрешений для этой презентации. Только для чтения [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Возвращает список всех разделов слайдов, определенных в презентации. Только для чтения [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Возвращает коллекцию меток чувствительности, применённых к документу презентации. Только для чтения [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Возвращает список всех слайдов, определённых в презентации. Только для чтения [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Возвращает настройки показа слайдов презентации. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Возвращает объект размера слайда. Только для чтения [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Возвращает информацию о том, из какого формата была загружена презентация. Только для чтения [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Получает или задает VBA-проект с макросами презентации. Чтение/запись [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Возвращает коллекцию всех встроенных видеофайлов в презентации. Только для чтения [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Получает глобальные свойства представления презентации. Только для чтения [`IViewProperties`](../iviewproperties). |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Освобождает все ресурсы, используемые этим объектом Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Возвращает объекты Image для всех слайдов презентации. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Возвращает объекты Thumbnail Image для указанных слайдов презентации. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Возвращает объект Slide, MasterSlide или LayoutSlide по Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Выделяет все совпадения регулярного выражения указанным цветом. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Выделяет все совпадения образца текста указанным цветом. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Выделяет все совпадения образца текста указанным цветом. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Объединяет последовательности с одинаковым форматированием во всех абзацах всех подходящих фигур во всех слайдах. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Заменяет все совпадения регулярного выражения указанной строкой. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Сохраняет все слайды презентации в поток в указанном формате. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Сохраняет все слайды презентации в файл в указанном формате. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Сохраняет указанные слайды презентации в поток в указанном формате, сохраняет номера страниц. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Сохраняет все слайды презентации в поток в указанном формате с дополнительными параметрами. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Сохраняет указанные слайды презентации в файл в указанном формате, сохраняет номера страниц. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в поток в указанном формате, сохраняет номера страниц. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Сохраняет указанные слайды презентации в файл в указанном формате, сохраняет номера страниц. |

### Примеры

Следующий пример показывает, как создать презентацию PowerPoint.

```csharp
[C#]
// Создать объект Presentation, представляющий файл презентации
using (Presentation presentation = new Presentation())
{
    // Получить первый слайд
    ISlide slide = presentation.Slides[0];
    // Добавить автоконтур типа линия
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Сохранить файл презентации.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Следующий пример показывает, как открыть и сохранить презентацию.

```csharp
[C#]
// Загрузить любой поддерживаемый файл в Presentation, например ppt, pptx, odp и т.д.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Сохранить файл презентации.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IPresentation](../ipresentation)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->