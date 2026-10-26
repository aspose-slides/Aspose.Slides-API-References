---
title: IBaseSlide class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ibaseslide/
---
## IBaseSlide класс

Представляет общие данные для всех типов слайдов.

Тип IBaseSlide раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/ibaseslide/shapes/) | Возвращает фигуры слайда.<br/>            Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/ibaseslide/controls/) | Возвращает коллекцию элементов управления ActiveX на слайде.<br/>            Только для чтения [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/ibaseslide/name/) | Возвращает или задает имя слайда.<br/>            Чтение/запись **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/ibaseslide/slide_id/) | Возвращает идентификатор слайда.<br/>            Только для чтения **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/ibaseslide/custom_data/) | Возвращает пользовательские данные слайда.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/ibaseslide/timeline/) | Возвращает объект временной шкалы анимации.<br/>            Только для чтения [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/ibaseslide/slide_show_transition/) | Возвращает объект TransitionEx, содержащий информацию о<br/>            том, как указанный слайд переходит в ходе показа.<br/>            Только для чтения [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/ibaseslide/background/) | Возвращает фон слайда.<br/>            Только для чтения [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/ibaseslide/hyperlink_queries/) | Обеспечивает простой доступ к содержащимся гиперссылкам.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/ibaseslide/show_master_shapes/) | Указывает, должны ли фигуры на главном слайде отображаться на остальных слайдах или нет.<br/>            Для самого главного слайда это свойство всегда возвращает `false`.<br/>            Чтение/запись **bool**. |
| [`slide`](/slides/python-net/ru/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/ibaseslide/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Объединяет последовательности с одинаковым форматированием во всех абзацах всех подходящих фигур. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/ibaseslide/equals/#ibaseslide) | Определяет, равны ли два экземпляра IBaseSlide.<br/>            Возвращаемое значение вычисляется на основе структуры слайда и статического содержания.<br/>            Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т.д. совпадают. При сравнении не учитываются уникальные идентификаторы, такие как SlideId, и динамическое содержание, например текущее значение даты в заполнителе даты. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)