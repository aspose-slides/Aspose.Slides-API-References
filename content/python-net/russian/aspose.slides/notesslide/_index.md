---
title: NotesSlide class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/notesslide/
---
## NotesSlide класс

Представляет слайд заметок в презентации.

**Inheritance:**[`NotesSlide`](/slides/python-net/ru/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)

Тип NotesSlide раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/notesslide/shapes/) | Возвращает формы слайда.<br/>            Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/notesslide/controls/) | Возвращает коллекцию элементов управления ActiveX на слайде.<br/>            Только для чтения [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/notesslide/name/) | Возвращает или задает имя слайда.<br/>            Чтение/запись **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/notesslide/slide_id/) | Возвращает идентификатор слайда.<br/>            Только для чтения **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/notesslide/custom_data/) | Возвращает пользовательские данные слайда.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/notesslide/timeline/) | Возвращает объект тайм-лайн анимации.<br/>            Только для чтения [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/notesslide/slide_show_transition/) | Возвращает объект Transition, содержащий информацию о том, как указанный слайд переходит во время показа.<br/>            Только для чтения [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/notesslide/background/) | Возвращает фон слайда.<br/>            Только для чтения [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/notesslide/hyperlink_queries/) | Обеспечивает простой доступ к содержащимся гиперссылкам.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/notesslide/show_master_shapes/) | Указывает, должны ли формы мастер-слайда отображаться на слайдах.<br/>            Чтение/запись **bool**. |
| [`presentation`](/slides/python-net/ru/aspose.slides/notesslide/presentation/) | Возвращает интерфейс IPresentation.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/notesslide/header_footer_manager/) | Возвращает менеджер HeaderFooter слайда заметок.<br/>            Только для чтения [`INotesSlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/ru/aspose.slides/notesslide/notes_text_frame/) | Возвращает TextFrame с текстом заметок, если он присутствует.<br/>            Только для чтения [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/notesslide/theme_manager/) | Возвращает переопределяющий менеджер темы.<br/>            Только для чтения [`IOverrideThemeManager`](/slides/python-net/ru/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/ru/aspose.slides/notesslide/parent_slide/) | Возвращает родительский слайд.<br/>            Только для чтения [`ISlide`](/slides/python-net/ru/aspose.slides/islide). |
| [`slide`](/slides/python-net/ru/aspose.slides/notesslide/slide/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Объединяет участки текста с одинаковым форматированием во всех абзацах всех подходящих форм. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ru/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Объединяет участки текста с одинаковым форматированием во всех абзацах во всех подходящих формах. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/notesslide/equals/#ibaseslide) | Определяет, равны ли два экземпляра IBaseSlide.<br/>            Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого.<br/>            Два слайда считаются равными, если все формы, стили, тексты, анимация и другие параметры и т.д. одинаковы. При сравнении не учитываются уникальные идентификаторы, такие как SlideId, и динамическое содержимое, например текущее значение даты в заполнителе даты. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/notesslide/create_theme_effective/#) | Возвращает эффективную тему для этого слайда. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Находит первое вхождение формы с указанным альтернативным текстом. |


### См. также
* класс [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)
* класс [`NotesSlide`](/slides/python-net/ru/aspose.slides/notesslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)