---
title: LayoutSlide class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/layoutslide/
---
## LayoutSlide класс

Представляет макетный слайд.

**Наследование:**[`LayoutSlide`](/slides/python-net/ru/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)

Тип LayoutSlide раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/layoutslide/shapes/) | Возвращает формы слайда.<br/>            Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/layoutslide/controls/) | Возвращает коллекцию элементов управления ActiveX на слайде.<br/>            Только для чтения [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/layoutslide/name/) | Возвращает или задаёт имя слайда.<br/>            Чтение/запись **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/layoutslide/slide_id/) | Возвращает идентификатор слайда.<br/>            Только для чтения **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/layoutslide/custom_data/) | Возвращает пользовательские данные слайда.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/layoutslide/timeline/) | Возвращает объект временной шкалы анимации.<br/>            Только для чтения [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/layoutslide/slide_show_transition/) | Возвращает объект Transition, который содержит информацию о<br/>            том, как указанный слайд переходит в ходе показа слайдов.<br/>            Только для чтения [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/layoutslide/background/) | Возвращает фон слайда.<br/>            Только для чтения [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/layoutslide/hyperlink_queries/) | Обеспечивает простой доступ к содержащимся гиперссылкам.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/layoutslide/show_master_shapes/) | Указывает, должны ли формы на мастер-слайде отображаться на слайдах или нет.<br/>            Чтение/запись **bool**. |
| [`presentation`](/slides/python-net/ru/aspose.slides/layoutslide/presentation/) | Возвращает интерфейс IPresentation.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/layoutslide/header_footer_manager/) | Возвращает менеджер HeaderFooter макетного слайда.<br/>            Только для чтения [`ILayoutSlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/ru/aspose.slides/layoutslide/placeholder_manager/) | Возвращает менеджер заполнителей макетного слайда.<br/>            Только для чтения [`ILayoutPlaceholderManager`](/slides/python-net/ru/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/ru/aspose.slides/layoutslide/master_slide/) | Возвращает или задаёт мастер-слайд для макета.<br/>            Чтение/запись [`IMasterSlide`](/slides/python-net/ru/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/layoutslide/theme_manager/) | Возвращает менеджер переопределяющей темы.<br/>            Только для чтения [`IOverrideThemeManager`](/slides/python-net/ru/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/ru/aspose.slides/layoutslide/layout_type/) | Возвращает тип макета этого макетного слайда.<br/>            Только для чтения [`SlideLayoutType`](/slides/python-net/ru/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/ru/aspose.slides/layoutslide/has_depending_slides/) | Возвращает true, если существует хотя бы один слайд, зависящий от этого макетного слайда.<br/>            Только для чтения **bool**. |
| [`drawing_guides`](/slides/python-net/ru/aspose.slides/layoutslide/drawing_guides/) | Возвращает коллекцию направляющих рисунка для макетного слайда.<br/>            Только для чтения [`IDrawingGuidesCollection`](/slides/python-net/ru/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ru/aspose.slides/layoutslide/slide/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Объединяет фрагменты с одинаковым форматированием во всех абзацах всех допустимых фигур. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ru/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Объединяет фрагменты с одинаковым форматированием во всех абзацах во всех допустимых фигурах. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/layoutslide/equals/#ibaseslide) | Определяет, равны ли два экземпляра IBaseSlide.<br/>            Возвращаемое значение рассчитывается на основе структуры слайда и статического контента.<br/>            Два слайда считаются равными, если все формы, стили, тексты, анимация и другие параметры и т.д. одинаковы. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамический контент, например текущее значение даты в заполняющем элементе Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/layoutslide/create_theme_effective/#) | Возвращает применяемую тему для этого слайда. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [`remove(self)`](/slides/python-net/ru/aspose.slides/layoutslide/remove/#) | Удаляет макет из презентации. |
| [`get_depending_slides(self)`](/slides/python-net/ru/aspose.slides/layoutslide/get_depending_slides/#) | Возвращает массив со всеми слайдами, зависящими от этого макетного слайда. |

### См. также
* класс [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)
* класс [`LayoutSlide`](/slides/python-net/ru/aspose.slides/layoutslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)