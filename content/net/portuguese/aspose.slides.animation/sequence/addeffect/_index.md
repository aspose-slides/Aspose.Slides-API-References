---
title: AddEffect
second_title: Referência da API Aspose.Sildes para .NET
description: Adiciona um novo efeito ao final da sequência.
type: docs
weight: 40
url: /pt/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Adiciona um novo efeito ao final da sequência.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | IShape | Objeto Shape [`IShape`](../../../aspose.slides/ishape) para adicionar um efeito |
| effectType | EffectType | Tipo de um efeito de animação [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efeito de animação [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de disparo do efeito [`EffectTriggerType`](../../effecttriggertype) |

### Valor de Retorno

Novo objeto effect [`IEffect`](../../ieffect)

### Veja Também

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* classe [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Adiciona um novo efeito de animação para o parágrafo ao final da sequência.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| paragraph | IParagraph | Objeto Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Tipo de um efeito de animação [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efeito de animação [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de disparo do efeito [`EffectTriggerType`](../../effecttriggertype) |

### Valor de Retorno

Novo objeto effect [`IEffect`](../../ieffect)

### Exemplos

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // selecione o parágrafo para adicionar o efeito
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // adiciona o efeito de animação Fly ao parágrafo selecionado
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Veja Também

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* classe [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chart | IChart | Objeto Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Tipo de um efeito de animação [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Índice Int32 |
| effectType | EffectType | Tipo de um efeito de animação [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efeito de animação [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de disparo do efeito [`EffectTriggerType`](../../effecttriggertype) |

### Valor de Retorno

Novo objeto effect [`IEffect`](../../ieffect)

### Veja Também

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* classe [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Adiciona o novo efeito de animação de gráfico para elementos em categoria ou série ao final da sequência.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chart | IChart | Objeto Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Tipo de um efeito de animação [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Índice da série do gráfico Int32 |
| categoriesIndex | Int32 | Índice da categoria Int32 |
| effectType | EffectType | Tipo de um efeito de animação [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efeito de animação [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de disparo do efeito [`EffectTriggerType`](../../effecttriggertype) |

### Valor de Retorno

Novo objeto effect [`IEffect`](../../ieffect)

### Veja Também

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* classe [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->