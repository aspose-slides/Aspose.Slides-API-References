---
title: SlideUtil class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.util/slideutil/
---
## SlideUtil класс

Предлагает методы, которые помогают искать фигуры и текст в презентации.

Тип SlideUtil раскрывает следующие члены:

## Методы

| Метод | Описание |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/ru/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Найти форму по альтернативному тексту в презентации PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/ru/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Найти форму по альтернативному тексту на слайде в презентации PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/ru/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Изменяет размещение всех форм на слайде. Выравнивает формы по полям или к краю слайда<br/>            или выравнивает их относительно друг друга. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/ru/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Изменяет размещение выбранных форм на слайде. Выравнивает формы по полям или к краю слайда<br/>            или выравнивает их относительно друг друга. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/ru/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Изменяет размещение всех форм внутри групповой формы. Выравнивает формы по полям или к краю слайда<br/>            или выравнивает их относительно друг друга. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/ru/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Изменяет размещение выбранных форм внутри групповой формы. Выравнивает формы по полям или к краю слайда<br/>            или выравнивает их относительно друг друга. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/ru/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Ищет все формы на указанном слайде, соответствующие заданному типу заполнителя. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/ru/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Находит и заменяет текст в презентации с заданным форматом. |
| [`get_all_text_boxes(slide)`](/slides/python-net/ru/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Возвращает все текстовые фреймы на слайде в презентации PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/ru/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Возвращает все текстовые фреймы на указанном слайде, содержащие данный текст. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/ru/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Возвращает все текстовые фреймы в презентации PPTX. |
| [`to_save_format(format)`](/slides/python-net/ru/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Преобразует формат исходного файла в соответствующий [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat). |


### См. также
* модуль [`aspose.slides.util`](/slides/python-net/ru/aspose.slides.util)
* библиотека [`Aspose.Slides`](/slides/python-net)