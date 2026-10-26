---
title: IDocumentProperties class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/idocumentproperties/
---
## IDocumentProperties класс

Represents properties of a presentation.

The IDocumentProperties type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/ru/aspose.slides/idocumentproperties/app_version/) | Возвращает версию приложения.<br/>            Read-only **str**. |
| [`name_of_application`](/slides/python-net/ru/aspose.slides/idocumentproperties/name_of_application/) | Возвращает или задает имя приложения.<br/>            Read/write **str**. |
| [`company`](/slides/python-net/ru/aspose.slides/idocumentproperties/company/) | Возвращает или задает свойство компании.<br/>            Read/write **str**. |
| [`manager`](/slides/python-net/ru/aspose.slides/idocumentproperties/manager/) | Возвращает или задает свойство менеджера.<br/>            Read/write **str**. |
| [`presentation_format`](/slides/python-net/ru/aspose.slides/idocumentproperties/presentation_format/) | Возвращает или задает предполагаемый формат презентации.<br/>            Read/write **str**. |
| [`shared_doc`](/slides/python-net/ru/aspose.slides/idocumentproperties/shared_doc/) | Определяет, является ли презентация общей для нескольких людей.<br/>            Read/write **bool**. |
| [`application_template`](/slides/python-net/ru/aspose.slides/idocumentproperties/application_template/) | Возвращает или задает шаблон приложения.<br/>            Read/write **str**. |
| [`total_editing_time`](/slides/python-net/ru/aspose.slides/idocumentproperties/total_editing_time/) | Общее время редактирования презентации.<br/>            Read/write **System.TimeSpan**. |
| [`title`](/slides/python-net/ru/aspose.slides/idocumentproperties/title/) | Возвращает или задает заголовок презентации.<br/>            Read/write **str**. |
| [`subject`](/slides/python-net/ru/aspose.slides/idocumentproperties/subject/) | Возвращает или задает тему презентации.<br/>            Read/write **str**. |
| [`author`](/slides/python-net/ru/aspose.slides/idocumentproperties/author/) | Возвращает или задает автора презентации.<br/>            Read/write **str**. |
| [`keywords`](/slides/python-net/ru/aspose.slides/idocumentproperties/keywords/) | Возвращает или задает ключевые слова презентации.<br/>            Read/write **str**. |
| [`comments`](/slides/python-net/ru/aspose.slides/idocumentproperties/comments/) | Возвращает или задает комментарии к презентации.<br/>            Read/write **str**. |
| [`category`](/slides/python-net/ru/aspose.slides/idocumentproperties/category/) | Возвращает или задает категорию презентации.<br/>            Read/write **str**. |
| [`created_time`](/slides/python-net/ru/aspose.slides/idocumentproperties/created_time/) | Возвращает дату создания презентации.<br/>            Значения в формате UTC.<br/>            Read/write **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/ru/aspose.slides/idocumentproperties/last_saved_time/) | Возвращает дату последнего изменения презентации.<br/>            Значения в формате UTC.P<br/>            Только для чтения в случае Presentation.DocumentProperties (поскольку он будет обновляться внутренне во время процесса сохранения объекта IPresentation). <br/>            Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [`IPresentationInfo.read_document_properties`](/slides/python-net/ru/aspose.slides/ipresentationinfo/read_document_properties)<br/>            См. пример в сводке метода **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**. |
| [`last_printed`](/slides/python-net/ru/aspose.slides/idocumentproperties/last_printed/) | Возвращает дату последней печати презентации.<br/>            Read/write **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/ru/aspose.slides/idocumentproperties/last_saved_by/) | Возвращает или задает имя последнего пользователя, изменившего презентацию.<br/>            Read/write **str**. |
| [`revision_number`](/slides/python-net/ru/aspose.slides/idocumentproperties/revision_number/) | Возвращает или задает номер редакции презентации.<br/>            Read/write **int**. |
| [`content_status`](/slides/python-net/ru/aspose.slides/idocumentproperties/content_status/) | Возвращает или задает статус содержания презентации.<br/>            Read/write **str**. |
| [`content_type`](/slides/python-net/ru/aspose.slides/idocumentproperties/content_type/) | Возвращает или задает тип содержания презентации.<br/>            Read/write **str**. |
| [`hyperlink_base`](/slides/python-net/ru/aspose.slides/idocumentproperties/hyperlink_base/) | Возвращает или задает свойство документа HyperlinkBase.<br/>            Read/write **str**. |
| [`scale_crop`](/slides/python-net/ru/aspose.slides/idocumentproperties/scale_crop/) | Указывает режим отображения миниатюры документа.<br/>            Установите значение **true**, чтобы масштабировать миниатюру документа под экран.<br/>            Установите значение **false**, чтобы обрезать миниатюру документа и показывать только те части, которые помещаются на экране.<br/>            Read/write **bool**. |
| [`links_up_to_date`](/slides/python-net/ru/aspose.slides/idocumentproperties/links_up_to_date/) | Указывает, актуальны ли гиперссылки в документе.<br/>            Установите значение **true**, чтобы указать, что гиперссылки обновлены.<br/>            Установите значение **false**, чтобы указать, что гиперссылки устарели.<br/>            Read/write **bool**. |
| [`hyperlinks_changed`](/slides/python-net/ru/aspose.slides/idocumentproperties/hyperlinks_changed/) | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем.<br/>            Следующий производитель, открывающий этот документ, должен обновить отношения гиперссылок новыми гиперссылками, указанными в этой части.<br/>            Read/write **bool**. |
| [`slides`](/slides/python-net/ru/aspose.slides/idocumentproperties/slides/) | Указывает общее количество слайдов в документе презентации.<br/ru/>            Read-only **int**. |
| [`hidden_slides`](/slides/python-net/ru/aspose.slides/idocumentproperties/hidden_slides/) | Указывает количество скрытых слайдов в документе презентации.<br/>            Read-only **int**. |
| [`notes`](/slides/python-net/ru/aspose.slides/idocumentproperties/notes/) | Указывает количество слайдов презентации, содержащих примечания.<br/>            Read-only **int**. |
| [`paragraphs`](/slides/python-net/ru/aspose.slides/idocumentproperties/paragraphs/) | Указывает общее количество абзацев в документе, если применимо.<br/>            Read-only **int**. |
| [`words`](/slides/python-net/ru/aspose.slides/idocumentproperties/words/) | Указывает общее количество слов в документе.<br/>            Read-only **int**. |
| [`multimedia_clips`](/slides/python-net/ru/aspose.slides/idocumentproperties/multimedia_clips/) | Указывает общее количество аудио- или видеоклипов, присутствующих в документе.<br/>            Read-only **int**. |
| [`titles_of_parts`](/slides/python-net/ru/aspose.slides/idocumentproperties/titles_of_parts/) | Указывает заголовок каждой части документа.<br/>            Эти части не являются частями документа, а концептуальными представлениями разделов документа.<br/>            Read-only **List[str]**. |
| [`heading_pairs`](/slides/python-net/ru/aspose.slides/idocumentproperties/heading_pairs/) | Указывает группировку частей документа и количество частей в каждой группе.<br/>            Read-only **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/ru/aspose.slides/idocumentproperties/count_of_custom_properties/) | Возвращает количество пользовательских свойств, фактически содержащихся в коллекции.<br/>            Read-only **int**. |

## Методы

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Получает именованное логическое значение из пользовательских свойств. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Получает именованное целочисленное значение из пользовательских свойств. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Получает именованное значение DateTime из пользовательских свойств. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Получает именованную строку из пользовательских свойств. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Устанавливает именованное логическое пользовательское свойство. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Устанавливает именованное целочисленное пользовательское свойство. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Устанавливает именованное пользовательское свойство DateTime. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Устанавливает именованное строковое пользовательское свойство. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Устанавливает именованное свойство типа float. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ru/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Устанавливает именованное свойство типа double. |
| [`get_custom_property_name(self, index)`](/slides/python-net/ru/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Возвращает имя пользовательского свойства по указанному индексу. |
| [`remove_custom_property(self, name)`](/slides/python-net/ru/aspose.slides/idocumentproperties/remove_custom_property/#str) | Удаляет пользовательское свойство, связанное с указанным именем. |
| [`contains_custom_property(self, name)`](/slides/python-net/ru/aspose.slides/idocumentproperties/contains_custom_property/#str) | Проверяет наличие пользовательского свойства с указанным именем. |
| [`clear_custom_properties(self)`](/slides/python-net/ru/aspose.slides/idocumentproperties/clear_custom_properties/#) | Удаляет все пользовательские свойства. |
| [`clear_built_in_properties(self)`](/slides/python-net/ru/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Очищает и задает значения по умолчанию для всех встроенных свойств. |
| [`get_sensitivity_labels(self)`](/slides/python-net/ru/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Получает массив меток чувствительности из пользовательских свойств документа (метаданные Microsoft Information Protection SDK). |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)