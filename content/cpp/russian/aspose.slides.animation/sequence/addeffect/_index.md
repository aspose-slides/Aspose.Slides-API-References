---
title: AddEffect()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет новый эффект в конец последовательности.
type: docs
weight: 157
url: /ru/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) метод

Добавляет новый эффект в конец последовательности.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) объект [IShape](../../../aspose.slides/ishape/) для добавления эффекта |
| effectType | [EffectType](../../effecttype/) | Тип анимационного эффекта [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Подтипы анимационного эффекта [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Тип триггера эффекта [EffectTriggerType](../../effecttriggertype/) |

### Возвращаемое значение

Новый объект эффекта [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) метод

Добавляет новый анимационный эффект для абзаца в конец последовательности.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) объект [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Тип анимационного эффекта [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Подтипы анимационного эффекта [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Тип триггера эффекта [EffectTriggerType](../../effecttriggertype/) |

### Возвращаемое значение

Новый объект эффекта [IEffect](../../ieffect/)

## Примечания

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// выберите абзац для добавления эффекта
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// добавьте эффект анимации Fly к выбранному абзацу
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) метод

Добавляет новый анимационный эффект диаграммы для категории или серии в конец последовательности.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Объект диаграммы [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Тип анимационного эффекта [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Индекс **int32_t** |
| effectType | [EffectType](../../effecttype/) | Тип анимационного эффекта [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Подтипы анимационного эффекта [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Тип триггера эффекта [EffectTriggerType](../../effecttriggertype/) |

### Возвращаемое значение

Новый объект эффекта [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) метод

Добавляет новый анимационный эффект диаграммы для элементов в категории или серии в конец последовательности.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Объект диаграммы [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Тип анимационного эффекта [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Индекс серии диаграммы **int32_t** |
| categoriesIndex | **int32_t** | Индекс категории **int32_t** |
| effectType | [EffectType](../../effecttype/) | Тип анимационного эффекта [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Подтипы анимационного эффекта [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Тип триггера эффекта [EffectTriggerType](../../effecttriggertype/) |

### Возвращаемое значение

Новый объект эффекта [IEffect](../../ieffect/)

## См. также

* Перечисление [EffectType](../../effecttype/)
* Перечисление [EffectSubtype](../../effectsubtype/)
* Перечисление [EffectTriggerType](../../effecttriggertype/)
* Перечисление [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Перечисление [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IEffect](../../ieffect/)
* Класс [IShape](../../../aspose.slides/ishape/)
* Класс [Sequence](../)
* Класс [IParagraph](../../../aspose.slides/iparagraph/)
* Класс [IChart](../../../aspose.slides.charts/ichart/)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)