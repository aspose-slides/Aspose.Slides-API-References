---
title: Presentation class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/presentation/
---
## Класс Presentation

Представляет презентацию Microsoft PowerPoint.

Тип Presentation раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#) | Этот конструктор создаёт новую презентацию с нуля.<br/>            Созданная презентация содержит один пустой слайд. |
| [`__init__(self, load_options)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#loadoptions) | Этот конструктор создаёт новую презентацию с нуля.<br/>            Созданная презентация содержит один пустой слайд. |
| [`__init__(self, stream)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#iorawiobase) | Этот конструктор является основным механизмом чтения существующей презентации. |
| [`__init__(self, stream, load_options)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Этот конструктор является основным механизмом чтения существующей презентации. |
| [`__init__(self, file)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#str) | Этот конструктор получает путь к исходному файлу, из которого<br/>             читается содержимое презентации. |
| [`__init__(self, file, load_options)`](/slides/python-net/ru/aspose.slides/presentation/__init__/#str-loadoptions) | Этот конструктор получает путь к исходному файлу, из которого<br/>            читается содержимое презентации. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`current_date_time`](/slides/python-net/ru/aspose.slides/presentation/current_date_time/) | Возвращает или задаёт дату и время, которые заменяют содержимое полей datetime.<br/>            Время создания данного объекта Presentation по умолчанию.<br/>            Чтение/запись **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/presentation/header_footer_manager/) | Возвращает текущий менеджер HeaderFooter.<br/>            Только для чтения [`IPresentationHeaderFooterManager`](/slides/python-net/ru/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ru/aspose.slides/presentation/protection_manager/) | Получает менеджер прав доступа для этой презентации.<br/>            Только для чтения [`IProtectionManager`](/slides/python-net/ru/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ru/aspose.slides/presentation/slides/) | Возвращает список всех слайдов, определённых в презентации.<br/ru/>            Только для чтения [`ISlideCollection`](/slides/python-net/ru/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ru/aspose.slides/presentation/sections/) | Возвращает список всех разделов слайдов, определённых в презентации.<br/>            Только для чтения [`ISectionCollection`](/slides/python-net/ru/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ru/aspose.slides/presentation/slide_size/) | Возвращает объект размера слайда.<br/>            Только для чтения [`ISlideSize`](/slides/python-net/ru/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ru/aspose.slides/presentation/notes_size/) | Возвращает объект размера слайда заметок.<br/>            Только для чтения [`INotesSize`](/slides/python-net/ru/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ru/aspose.slides/presentation/layout_slides/) | Возвращает список всех шаблонных слайдов, определённых в презентации.<br/>            Только для чтения [`IGlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ru/aspose.slides/presentation/masters/) | Возвращает список всех мастер-слайдов, определённых в презентации.<br/>            Только для чтения [`IMasterSlideCollection`](/slides/python-net/ru/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ru/aspose.slides/presentation/master_notes_slide_manager/) | Возвращает менеджер мастера заметок.<br/>            Только для чтения [`IMasterNotesSlideManager`](/slides/python-net/ru/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ru/aspose.slides/presentation/master_handout_slide_manager/) | Возвращает менеджер мастера раздаточных материалов.<br/>            Только для чтения [`IMasterHandoutSlideManager`](/slides/python-net/ru/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ru/aspose.slides/presentation/fonts_manager/) | Возвращает менеджер шрифтов.<br/>            Только для чтения [`IFontsManager`](/slides/python-net/ru/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ru/aspose.slides/presentation/default_text_style/) | Возвращает стиль текста по умолчанию для фигур.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ru/aspose.slides/presentation/comment_authors/) | Возвращает коллекцию авторов комментариев.<br/>            Только для чтения [`ICommentAuthorCollection`](/slides/python-net/ru/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ru/aspose.slides/presentation/document_properties/) | Возвращает объект DocumentProperties, содержащий стандартные и пользовательские свойства документа.<br/>            Только для чтения [`IDocumentProperties`](/slides/python-net/ru/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ru/aspose.slides/presentation/images/) | Возвращает коллекцию всех изображений в презентации.<br/>            Только для чтения [`IImageCollection`](/slides/python-net/ru/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ru/aspose.slides/presentation/audios/) | Возвращает коллекцию всех встроенных аудиофайлов в презентации.<br/>            Только для чтения [`IAudioCollection`](/slides/python-net/ru/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ru/aspose.slides/presentation/videos/) | Возвращает коллекцию всех встроенных видеофайлов в презентации.<br/>            Только для чтения [`IVideoCollection`](/slides/python-net/ru/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/ru/aspose.slides/presentation/slide_show_settings/) | Возвращает настройки слайд-шоу для презентации. |
| [`digital_signatures`](/slides/python-net/ru/aspose.slides/presentation/digital_signatures/) | Возвращает коллекцию подписей, использованных для подписи презентации.<br/>            Только для чтения [`IDigitalSignatureCollection`](/slides/python-net/ru/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/presentation/custom_data/) | Возвращает пользовательские данные презентации.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/ru/aspose.slides/presentation/all_custom_xml_parts/) | Возвращает все пользовательские части данных в презентации.<br/>            Только для чтения [`ICustomXmlPart`](/slides/python-net/ru/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/ru/aspose.slides/presentation/vba_project/) | Получает или задаёт проект VBA с макросами презентации.<br/>            Чтение/запись [`IVbaProject`](/slides/python-net/ru/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/presentation/hyperlink_queries/) | Обеспечивает простой доступ ко всем гиперссылкам, содержащимся во всех слайдах презентации (не в мастерах, шаблонах, слайдах заметок).<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ru/aspose.slides/presentation/view_properties/) | Получает свойства представления, применимые к всей презентации.<br/>            Только для чтения [`IViewProperties`](/slides/python-net/ru/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ru/aspose.slides/presentation/first_slide_number/) | Представляет номер первого слайда в презентации |
| [`sensitivity_labels`](/slides/python-net/ru/aspose.slides/presentation/sensitivity_labels/) | Возвращает коллекцию меток конфиденциальности, применённых к документу презентации.<br/>            Только для чтения [`ISensitivityLabelCollection`](/slides/python-net/ru/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/ru/aspose.slides/presentation/source_format/) | Возвращает информацию о формате, из которого была загружена презентация.<br/>            Только для чтения [`SourceFormat`](/slides/python-net/ru/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/ru/aspose.slides/presentation/master_theme/) | Возвращает мастер-тему.<br/>            Только для чтения [`IMasterTheme`](/slides/python-net/ru/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/ru/aspose.slides/presentation/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ru/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Сохраняет все слайды презентации в файл указанного формата. |
| [`save(self, stream, format)`](/slides/python-net/ru/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Сохраняет все слайды презентации в поток в указанном формате. |
| [`save(self, fname, format, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Сохраняет все слайды презентации в поток в указанном формате и с дополнительными параметрами. |
| [`save(self, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/ru/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Сохраняет указанные слайды презентации в файл указанного формата с сохранением номеров страниц. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Сохраняет указанные слайды презентации в файл указанного формата с сохранением номеров страниц. |
| [`save(self, stream, slides, format)`](/slides/python-net/ru/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ru/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц. |
| [`get_images(self, options)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Возвращает объекты Image для всех слайдов презентации. |
| [`get_images(self, options, slides)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Возвращает объекты Thumbnail Image для указанных слайдов презентации. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием. |
| [`get_images(self, options, image_size)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ru/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ru/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Выделяет все совпадения образца текста указанным цветом. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ru/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Выделяет все совпадения образца текста указанным цветом. |
| [`get_slide_by_id(self, id)`](/slides/python-net/ru/aspose.slides/presentation/get_slide_by_id/#int) | Возвращает Slide, MasterSlide или LayoutSlide по Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/presentation/join_portions_with_same_formatting/#) | Объединяет фрагменты с одинаковым форматированием во всех абзацах во всех допустимых фигурах во всех слайдах. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ru/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Выделяет все совпадения регулярного выражения указанным цветом. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ru/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ru/aspose.slides/presentation/replace_regex/#str-str) | Заменяет все совпадения регулярного выражения указанной строкой. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)