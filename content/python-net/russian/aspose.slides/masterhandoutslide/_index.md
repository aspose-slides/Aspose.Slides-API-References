---
title: MasterHandoutSlide class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide класс

Представляет мастер-слайд для раздаточных материалов.

**Наследование:**[`MasterHandoutSlide`](/slides/python-net/ru/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)

Тип MasterHandoutSlide раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/masterhandoutslide/shapes/) | Возвращает фигуры слайда.<br/> Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/masterhandoutslide/controls/) | Возвращает коллекцию элементов управления ActiveX на слайде.<br/> Только для чтения [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/masterhandoutslide/name/) | Возвращает или задает имя слайда.<br/> Чтение/запись **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/masterhandoutslide/slide_id/) | Возвращает идентификатор слайда.<br/> Только для чтения **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/masterhandoutslide/custom_data/) | Возвращает пользовательские данные слайда.<br/> Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/masterhandoutslide/timeline/) | Возвращает объект временной шкалы анимации.<br/> Только для чтения [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/masterhandoutslide/slide_show_transition/) | Возвращает объект Transition, содержащий информацию о<br/> том, как указанный слайд переходит во время показа слайдов.<br/> Только для чтения [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/masterhandoutslide/background/) | Возвращает фон слайда.<br/> Только для чтения [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/masterhandoutslide/hyperlink_queries/) | Обеспечивает простой доступ к содержащимся гиперссылкам.<br/> Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/masterhandoutslide/show_master_shapes/) | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах или нет.<br/> Для самого мастер-слайда это свойство всегда возвращает `false`.<br/> Чтение/запись **bool**. |
| [`presentation`](/slides/python-net/ru/aspose.slides/masterhandoutslide/presentation/) | Возвращает интерфейс IPresentation.<br/> Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/masterhandoutslide/header_footer_manager/) | Возвращает менеджер HeaderFooter мастер-слайда раздаточного материала.<br/> Только для чтения [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/masterhandoutslide/theme_manager/) | Возвращает менеджер темы.<br/> Только для чтения [`IMasterThemeManager`](/slides/python-net/ru/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/ru/aspose.slides/masterhandoutslide/drawing_guides/) | Возвращает коллекцию руководств по рисованию для мастер-слайда раздаточного материала.<br/> Только для чтения [`IDrawingGuidesCollection`](/slides/python-net/ru/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ru/aspose.slides/masterhandoutslide/slide/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Объединяет участки текста с одинаковым форматированием во всех абзацах всех приемлемых фигур. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ru/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Объединяет участки текста с одинаковым форматированием во всех абзацах во всех приемлемых фигурах. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Определяет, равны ли два экземпляра IBaseSlide.<br/> Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого.<br/> Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущее значение даты в заполнитель даты. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/masterhandoutslide/create_theme_effective/#) | Возвращает эффективную тему для этого слайда. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Находит первое вхождение фигуры с указанным альтернативным текстом. |

### См. также
* класс [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)
* класс [`MasterHandoutSlide`](/slides/python-net/ru/aspose.slides/masterhandoutslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)