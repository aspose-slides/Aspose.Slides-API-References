---
title: Sequence class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.animation/sequence/
---
## Sequence класс

Представляет последовательность (коллекцию эффектов).

Тип Sequence предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/ru/aspose.slides.animation/sequence/count/) | Возвращает количество эффектов в последовательности.<br/>            Точно для чтения **int**. |
| [`trigger_shape`](/slides/python-net/ru/aspose.slides.animation/sequence/trigger_shape/) | Возвращает или задает целевой объект формы для ИНТЕРАКТИВНОЙ последовательности.<br/>            Если последовательность не интерактивна, то возвращает None.<br/>            Чтение/запись [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |

Возвращает эффект по указанному индексу.

## Индексатор

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.animation/sequence/__getitem__/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/ru/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Добавляет новый эффект в конец последовательности. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/ru/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Добавляет новый анимационный эффект для абзаца в конец последовательности. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/ru/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Добавляет новый анимационный эффект диаграммы для категории или серии в конец последовательности. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/ru/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Добавляет новый анимационный эффект диаграммы для элементов в категории или серии в конец последовательности. |
| [`remove(self, item)`](/slides/python-net/ru/aspose.slides.animation/sequence/remove/#ieffect) | Удаляет указанный эффект из коллекции. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides.animation/sequence/remove_at/#int) | Удаляет эффект из коллекции. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides.animation/sequence/clear/#) | Удаляет все эффекты из коллекции. |
| [`remove_by_shape(self, shape)`](/slides/python-net/ru/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Удаляет эффект для указанной формы. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/ru/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Возвращает массив эффектов для указанной формы. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/ru/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Возвращает массив эффектов для указанного абзаца. |
| [`get_count(self, shape)`](/slides/python-net/ru/aspose.slides.animation/sequence/get_count/#ishape) | Возвращает количество эффектов для указанной формы. |


### Смотрите также
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)