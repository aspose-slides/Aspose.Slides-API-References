---
title: MasterSlide class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/masterslide/
---
## MasterSlide класс

Представляет мастер-слайд в презентации.

**Наследование:**[`MasterSlide`](/slides/python-net/ru/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)

Тип MasterSlide раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/masterslide/shapes/) | Возвращает фигуры слайда.<br/>            Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/masterslide/controls/) | Возвращает коллекцию элементов управления ActiveX на слайде.<br/>            Только для чтения [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/masterslide/name/) | Возвращает или задает имя мастер-слайда.<br/>            Чтение/запись **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/masterslide/slide_id/) | Возвращает идентификатор слайда.<br/>            Только для чтения **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/masterslide/custom_data/) | Возвращает пользовательские данные слайда.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/masterslide/timeline/) | Возвращает объект временной шкалы анимации.<br/>            Только для чтения [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/masterslide/slide_show_transition/) | Возвращает объект Transition, содержащий информацию о том, как указанный слайд продвигается во время показа.<br/>            Только для чтения [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/masterslide/background/) | Возвращает фон слайда.<br/>            Только для чтения [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/masterslide/hyperlink_queries/) | Предоставляет простой доступ к содержащимся гиперссылкам.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/masterslide/show_master_shapes/) | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах.<br/>            Для самого мастер-слайда это свойство всегда возвращает `false`.<br/>            Чтение/запись **bool**. |
| [`presentation`](/slides/python-net/ru/aspose.slides/masterslide/presentation/) | Возвращает интерфейс IPresentation.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/masterslide/header_footer_manager/) | Возвращает менеджер HeaderFooter мастер-слайда.<br/>            Только для чтения [`IMasterSlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/ru/aspose.slides/masterslide/title_style/) | Возвращает стиль текста заголовка.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/ru/aspose.slides/masterslide/body_style/) | Возвращает стиль основного текста.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/ru/aspose.slides/masterslide/other_style/) | Возвращает стиль другого текста.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/ru/aspose.slides/masterslide/layout_slides/) | Возвращает коллекцию дочерних макетных слайдов для этого мастер-слайда.<br/>            Только для чтения [`IMasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/ru/aspose.slides/masterslide/preserve/) | Определяет, будет ли соответствующий мастер удалён, когда удалятся все слайды, использующие этот мастер.<br/>            Примечание: Aspose.Slides никогда не удаляет неиспользуемый мастер автоматически; для фактического удаления вызовите **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Чтение/запись **bool**. |
| [`has_depending_slides`](/slides/python-net/ru/aspose.slides/masterslide/has_depending_slides/) | Возвращает true, если существует хотя бы один слайд, зависящий от этого мастер-слайда.<br/>            Только для чтения **bool**. |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/masterslide/theme_manager/) | Возвращает менеджер темы.<br/>            Только для чтения [`IMasterThemeManager`](/slides/python-net/ru/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/ru/aspose.slides/masterslide/drawing_guides/) | Возвращает коллекцию направляющих для мастер-слайда.<br/>            Только для чтения [`IDrawingGuidesCollection`](/slides/python-net/ru/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ru/aspose.slides/masterslide/slide/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Объединяет участки с одинаковым форматированием во всех абзацах всех допустимых фигур. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ru/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Объединяет участки с одинаковым форматированием во всех абзацах во всех допустимых фигурах. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/masterslide/equals/#ibaseslide) | Определяет, равны ли два экземпляра IBaseSlide.<br/>            Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого.<br/>            Два слайда считаются равными, если все фигуры, стили, тексты, анимация и прочие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущее значение даты в заполняемом поле даты. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/masterslide/create_theme_effective/#) | Возвращает эффективную тему для этого слайда. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/ru/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Создаёт новый мастер-слайд на основе текущего, применяя к нему внешнюю тему, и применяет созданный мастер-слайд ко всем зависимым слайдам. |
| [`get_depending_slides(self)`](/slides/python-net/ru/aspose.slides/masterslide/get_depending_slides/#) | Возвращает массив всех слайдов, зависящих от этого мастер-слайда. |

### См. также
* класс [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)
* класс [`MasterSlide`](/slides/python-net/ru/aspose.slides/masterslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)