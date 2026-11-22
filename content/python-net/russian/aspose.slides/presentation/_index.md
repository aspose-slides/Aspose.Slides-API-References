---
title: Presentation class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/presentation/
---
## Presentation класс

Represents a Microsoft PowerPoint presentation.

The Presentation type exposes the following members:

## Конструкторы

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#) | Этот конструктор создает новую презентацию с нуля.<br/>            Созданная презентация содержит один пустой слайд. |
| [`__init__(self, load_options)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#loadoptions) | Этот конструктор создает новую презентацию с нуля.<br/>            Созданная презентация содержит один пустой слайд. |
| [`__init__(self, stream)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#iorawiobase) | Этот конструктор является основным механизмом чтения существующей презентации. |
| [`__init__(self, stream, load_options)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Этот конструктор является основным механизмом чтения существующей презентации. |
| [`__init__(self, file)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#str) | Этот конструктор получает путь к исходному файлу, из которого<br/>             содержимое презентации читается. |
| [`__init__(self, file, load_options)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#str-loadoptions) | Этот конструктор получает путь к исходному файлу, из которого<br/>            содержимое презентации читается. |

## Свойства

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/ru/aspose.slides/presentation/current_date_time/) | Возвращает или задает дату и время, которые заменят содержимое полей datetime.<br/>            Время создания данного объекта Presentation по умолчанию.<br/>            Чтение/запись **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/presentation/header_footer_manager/) | Возвращает текущий менеджер HeaderFooter.<br/>            Только чтение [`IPresentationHeaderFooterManager`](/slides/python-net/ru/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ru/aspose.slides/presentation/protection_manager/) | Получает менеджер разрешений для этой презентации.<br/>            Только чтение [`IProtectionManager`](/slides/python-net/ru/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ru/aspose.slides/presentation/slides/) | Возвращает список всех слайдов, определённых в презентации.<br/ru/>            Только чтение [`ISlideCollection`](/slides/python-net/ru/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ru/aspose.slides/presentation/sections/) | Возвращает список всех секций слайдов, определённых в презентации.<br/>            Только чтение [`ISectionCollection`](/slides/python-net/ru/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ru/aspose.slides/presentation/slide_size/) | Возвращает объект размера слайда.<br/>            Только чтение [`ISlideSize`](/slides/python-net/ru/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ru/aspose.slides/presentation/notes_size/) | Возвращает объект размера слайдов заметок.<br/>            Только чтение [`INotesSize`](/slides/python-net/ru/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ru/aspose.slides/presentation/layout_slides/) | Возвращает список всех слайдов макета, определённых в презентации.<br/>            Только чтение [`IGlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ru/aspose.slides/presentation/masters/) | Возвращает список всех главных слайдов, определённых в презентации.<br/>            Только чтение [`IMasterSlideCollection`](/slides/python-net/ru/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ru/aspose.slides/presentation/master_notes_slide_manager/) | Возвращает менеджер главных заметок.<br/>            Только чтение [`IMasterNotesSlideManager`](/slides/python-net/ru/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ru/aspose.slides/presentation/master_handout_slide_manager/) | Возвращает менеджер главных раздаточных материалов.<br/>            Только чтение [`IMasterHandoutSlideManager`](/slides/python-net/ru/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ru/aspose.slides/presentation/fonts_manager/) | Возвращает менеджер шрифтов.<br/>            Только чтение [`IFontsManager`](/slides/python-net/ru/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ru/aspose.slides/presentation/default_text_style/) | Возвращает стиль текста по умолчанию для фигур.<br/>            Только чтение [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ru/aspose.slides/presentation/comment_authors/) | Возвращает коллекцию авторов комментариев.<br/>            Только чтение [`ICommentAuthorCollection`](/slides/python-net/ru/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ru/aspose.slides/presentation/document_properties/) | Возвращает объект DocumentProperties, содержащий стандартные и пользовательские свойства документа.<br/>            Только чтение [`IDocumentProperties`](/slides/python-net/ru/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ru/aspose.slides/presentation/images/) | Возвращает коллекцию всех изображений в презентации.<br/>            Только чтение [`IImageCollection`](/slides/python-net/ru/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ru/aspose.slides/presentation/audios/) | Возвращает коллекцию всех встроенных аудиофайлов в презентации.<br/>            Только чтение [`IAudioCollection`](/slides/python-net/ru/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ru/aspose.slides/presentation/videos/) | Возвращает коллекцию всех встроенных видеофайлов в презентации.<br/>            Только чтение [`IVideoCollection`](/slides/python-net/ru/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/ru/aspose.slides/presentation/slide_show_settings/) | Возвращает настройки показа слайдов для презентации. |
| [`digital_signatures`](/slides/python-net/ru/aspose.slides/presentation/digital_signatures/) | Возвращает коллекцию подписей, используемых для подписи презентации.<br/>            Только чтение [`IDigitalSignatureCollection`](/slides/python-net/ru/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/presentation/custom_data/) | Возвращает пользовательские данные презентации.<br/>            Только чтение [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/ru/aspose.slides/presentation/all_custom_xml_parts/) | Возвращает все пользовательские части данных в презентации.<br/>            Только чтение [`ICustomXmlPart`](/slides/python-net/ru/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/ru/aspose.slides/presentation/vba_project/) | Получает или задает проект VBA с макросами презентации.<br/>            Чтение/запись [`IVbaProject`](/slides/python-net/ru/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/presentation/hyperlink_queries/) | Обеспечивает простой доступ ко всем гиперссылкам, содержащимся во всех слайдах презентации (не в главных, макетных, слайдах заметок).<br/>            Только чтение [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ru/aspose.slides/presentation/view_properties/) | Получает свойства представления, охватывающие всю презентацию.<br/>            Только чтение [`IViewProperties`](/slides/python-net/ru/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ru/aspose.slides/presentation/first_slide_number/) | Представляет номер первого слайда в презентации |
| [`sensitivity_labels`](/slides/python-net/ru/aspose.slides/presentation/sensitivity_labels/) | Возвращает коллекцию меток чувствительности, применённых к документу презентации.<br/>            Только чтение [`ISensitivityLabelCollection`](/slides/python-net/ru/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/ru/aspose.slides/presentation/source_format/) | Возвращает информацию о том, из какого формата была загружена презентация.<br/>            Только чтение [`SourceFormat`](/slides/python-net/ru/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/ru/aspose.slides/presentation/master_theme/) | Возвращает главную тему.<br/>            Только чтение [`IMasterTheme`](/slides/python-net/ru/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/ru/aspose.slides/presentation/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ru/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Сохраняет все слайды презентации в файл в указанном формате. |
| [`save(self, stream, format)`](/slides/python-net/ru/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Сохраняет все слайды презентации в поток в указанном формате. |
| [`save(self, fname, format, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Сохраняет все слайды презентации в поток в указанном формате с дополнительными параметрами. |
| [`save(self, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/ru/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Сохраняет указанные слайды презентации в файл в указанном формате с сохранением номеров страниц. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Сохраняет указанные слайды презентации в файл в указанном формате с сохранением номеров страниц. |
| [`save(self, stream, slides, format)`](/slides/python-net/ru/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц. |
| [`get_images(self, options)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Возвращает объекты Image для всех слайдов презентации. |
| [`get_images(self, options, slides)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Возвращает объекты Thumbnail Image для указанных слайдов презентации. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием. |
| [`get_images(self, options, image_size)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ru/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Подсвечивает все совпадения образца текста указанным цветом. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ru/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Подсвечивает все совпадения образца текста указанным цветом. |
| [`get_slide_by_id(self, id)`](/slides/python-net/ru/aspose.slides/presentation/get_slide_by_id/#int) | Возвращает объект Slide, MasterSlide или LayoutSlide по Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/presentation/join_portions_with_same_formatting/#) | Объединяет участки текста с одинаковым форматированием во всех абзацах во всех допустимых фигурах на всех слайдах. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ru/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Подсвечивает все совпадения регулярного выражения указанным цветом. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ru/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ru/aspose.slides/presentation/replace_regex/#str-str) | Заменяет все совпадения регулярного выражения указанной строкой. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/ru/aspose.slides/presentation/refresh_charts_data/#bool) | Перезагружает данные всех диаграмм в презентации из их исходных рабочих книг. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)