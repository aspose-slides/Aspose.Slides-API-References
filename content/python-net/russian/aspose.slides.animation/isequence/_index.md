---
title: ISequence class
second_title: Aspose.Slides для Python через .NET API Справка
description: 
type: docs
url: /ru/aspose.slides.animation/isequence/
---
## ISequence класс

Представляет последовательность (коллекцию эффектов).

Тип ISequence предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`count`](/slides/python-net/ru/aspose.slides.animation/isequence/count/) | Returns the number of effects in a sequense.<br/>            Только для чтения **int**. |
| [`trigger_shape`](/slides/python-net/ru/aspose.slides.animation/isequence/trigger_shape/) | Returns or sets shape target for INTERACTIVE sequence.<br/>            If sequence is not interactive then returns None.<br/>            Чтение/запись [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |

Возвращает эффект по указанному индексу.

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.animation/isequence/__getitem__/) | Индекс |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/ru/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Добавить новый эффект в конец последовательности. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/ru/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Добавить новый анимационный эффект для абзаца в конец последовательности. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/ru/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Adds the new chart animation effect for category or series to the end of sequence. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/ru/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Adds the new chart animation effect for elements in category or series to the end of sequence. |
| [`remove(self, item)`](/slides/python-net/ru/aspose.slides.animation/isequence/remove/#ieffect) | Удалить указанный эффект из коллекции. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides.animation/isequence/remove_at/#int) | Удалить эффект из коллекции. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides.animation/isequence/clear/#) | Удалить все эффекты из коллекции. |
| [`remove_by_shape(self, shape)`](/slides/python-net/ru/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Удалить эффект для указанной формы. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/ru/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Возвращает массив эффектов для указанной формы. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/ru/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Возвращает массив эффектов для указанного абзаца. |
| [`get_count(self, shape)`](/slides/python-net/ru/aspose.slides.animation/isequence/get_count/#ishape) | Возвращает количество эффектов для указанной формы. |


### См. также
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)