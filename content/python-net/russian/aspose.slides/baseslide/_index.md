---
title: BaseSlide class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/baseslide/
---
## BaseSlide класс

Представляет общие данные для всех типов слайдов.

Тип BaseSlide раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/baseslide/shapes/) | Возвращает формы слайда.<br/>            Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/baseslide/controls/) | Возвращает коллекцию элементов управления ActiveX на слайде.<br/>            Только для чтения [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/baseslide/name/) | Возвращает или задает имя слайда.<br/>            Чтение/запись **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/baseslide/slide_id/) | Возвращает идентификатор слайда.<br/>            Только для чтения **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/baseslide/custom_data/) | Возвращает пользовательские данные слайда.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/baseslide/timeline/) | Возвращает объект временной шкалы анимации.<br/>            Только для чтения [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/baseslide/slide_show_transition/) | Возвращает объект Transition, который содержит информацию о<br/>            том, как указанный слайд переходит во время показа слайдов.<br/>            Только для чтения [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/baseslide/background/) | Возвращает фон слайда.<br/>            Только для чтения [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/baseslide/hyperlink_queries/) | Обеспечивает простой доступ к содержащимся гиперссылкам.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/baseslide/show_master_shapes/) | Указывает, должны ли формы на главном слайде отображаться на слайдах или нет.<br/>            Для самого главного слайда это свойство всегда возвращает `false`.<br/>            Чтение/запись **bool**. |
| [`presentation`](/slides/python-net/ru/aspose.slides/baseslide/presentation/) | Возвращает интерфейс IPresentation.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/ru/aspose.slides/baseslide/slide/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Объединяет участки текста с одинаковым форматированием во всех абзацах всех приемлемых фигур. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ru/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Объединяет участки текста с одинаковым форматированием во всех абзацах во всех приемлемых фигурах. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/baseslide/equals/#ibaseslide) | Определяет, равны ли два экземпляра IBaseSlide.<br/>            Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого.<br/>            Два слайда считаются равными, если все формы, стили, тексты, анимация и другие настройки и т.д. одинаковы. При сравнении не учитываются уникальные значения идентификаторов, например SlideId, и динамическое содержимое, например текущее значение даты в заполнитель даты. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/baseslide/create_theme_effective/#) | Возвращает эффективную тему для этого слайда. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Находит первое вхождение фигуры с указанным альтернативным текстом. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)