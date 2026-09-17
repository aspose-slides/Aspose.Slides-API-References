---
title: add_effect method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Добавить новый эффект в конец последовательности.

### Возвращаемое значение

Новый объект эффекта [`IEffect`](/slides/python-net/ru/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Объект Shape [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для добавления эффекта |
| effect_type | [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) | Тип анимационного эффекта [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) | Подтипы анимационного эффекта [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) | Тип триггера эффекта [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Добавить новый анимационный эффект для абзаца в конец последовательности.

### Возвращаемое значение

Новый объект эффекта [`IEffect`](/slides/python-net/ru/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/ru/aspose.slides/iparagraph) | Объект Paragraph [`IParagraph`](/slides/python-net/ru/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) | Тип анимационного эффекта [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) | Подтипы анимационного эффекта [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) | Тип триггера эффекта [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Добавляет новый анимационный эффект диаграммы для категории или серии в конец последовательности.

### Возвращаемое значение

Новый объект эффекта [`IEffect`](/slides/python-net/ru/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart) | Объект Chart [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/ru/aspose.slides.animation/effectchartmajorgroupingtype) | Тип анимационного эффекта [`EffectChartMinorGroupingType`](/slides/python-net/ru/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Индекс **int** |
| effect_type | [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) | Тип анимационного эффекта [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) | Подтипы анимационного эффекта [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) | Тип триггера эффекта [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Добавляет новый анимационный эффект диаграммы для элементов в категории или серии в конец последовательности.

### Возвращаемое значение

Новый объект эффекта [`IEffect`](/slides/python-net/ru/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart) | Объект Chart [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/ru/aspose.slides.animation/effectchartminorgroupingtype) | Тип анимационного эффекта [`EffectChartMinorGroupingType`](/slides/python-net/ru/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Индекс серии диаграммы **int** |
| categories_index | **int** | Индекс категории **int** |
| effect_type | [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) | Тип анимационного эффекта [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) | Подтипы анимационного эффекта [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) | Тип триггера эффекта [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) |



### Смотрите также
* перечисление [`EffectChartMajorGroupingType`](/slides/python-net/ru/aspose.slides.animation/effectchartmajorgroupingtype)
* перечисление [`EffectChartMinorGroupingType`](/slides/python-net/ru/aspose.slides.animation/effectchartminorgroupingtype)
* перечисление [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype)
* перечисление [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype)
* перечисление [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype)
* класс [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart)
* класс [`IEffect`](/slides/python-net/ru/aspose.slides.animation/ieffect)
* класс [`IParagraph`](/slides/python-net/ru/aspose.slides/iparagraph)
* класс [`ISequence`](/slides/python-net/ru/aspose.slides.animation/isequence)
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)