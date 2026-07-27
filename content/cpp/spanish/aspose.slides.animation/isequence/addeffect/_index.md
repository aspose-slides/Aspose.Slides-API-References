---
title: AddEffect()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agregar un nuevo efecto al final de la secuencia.
type: docs
weight: 144
url: /es/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) method

Agregar un nuevo efecto al final de la secuencia.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | objeto [Shape](../../../aspose.slides/shape/) [IShape](../../../aspose.slides/ishape/) para agregar un efecto |
| effectType | [EffectType](../../effecttype/) | Tipo de un efecto de animación [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos del efecto de animación [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de activación del efecto [EffectTriggerType](../../effecttriggertype/) |

### Valor devuelto

Nuevo objeto de efecto [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) method

Agregar un nuevo efecto de animación para el párrafo al final de la secuencia.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | objeto [Paragraph](../../../aspose.slides/paragraph/) [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Tipo de un efecto de animación [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos del efecto de animación [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de activación del efecto [EffectTriggerType](../../effecttriggertype/) |

### Valor devuelto

Nuevo objeto de efecto [IEffect](../../ieffect/)

## Observaciones

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// seleccionar párrafo para agregar efecto
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// agregar efecto de animación Fly al párrafo seleccionado
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

Agrega el nuevo efecto de animación de gráfico para categoría o serie al final de la secuencia.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | objeto Chart [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Tipo de un efecto de animación [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Índice **int32_t** |
| effectType | [EffectType](../../effecttype/) | Tipo de un efecto de animación [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos del efecto de animación [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de activación del efecto [EffectTriggerType](../../effecttriggertype/) |

### Valor devuelto

Nuevo objeto de efecto [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

Agrega el nuevo efecto de animación de gráfico para elementos en categoría o serie al final de la secuencia.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | objeto Chart [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Tipo de un efecto de animación [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Índice de la serie del gráfico **int32_t** |
| categoriesIndex | **int32_t** | Índice de la categoría **int32_t** |
| effectType | [EffectType](../../effecttype/) | Tipo de un efecto de animación [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos del efecto de animación [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de activación del efecto [EffectTriggerType](../../effecttriggertype/) |

### Valor devuelto

Nuevo objeto de efecto [IEffect](../../ieffect/)

## Ver también

* Enumeración [EffectType](../../effecttype/)
* Enumeración [EffectSubtype](../../effectsubtype/)
* Enumeración [EffectTriggerType](../../effecttriggertype/)
* Enumeración [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enumeración [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IEffect](../../ieffect/)
* Clase [IShape](../../../aspose.slides/ishape/)
* Clase [ISequence](../)
* Clase [IParagraph](../../../aspose.slides/iparagraph/)
* Clase [IChart](../../../aspose.slides.charts/ichart/)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)