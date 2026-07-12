---
title: ISequence
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de efeitos em sequência.
type: docs
url: /pt/com.aspose.slides/isequence/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Representa uma sequência (coleção de efeitos).
## Métodos

| Método | Descrição |
| --- | --- |
| [getCount()](#getCount--) | Retorna o número de efeitos em uma sequência. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Remove o efeito especificado de uma coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove um efeito de uma coleção. |
| [clear()](#clear--) | Remove todos os efeitos de uma coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna um efeito no índice especificado. |
| [getTriggerShape()](#getTriggerShape--) | Retorna ou define o alvo da forma para a sequência INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Retorna ou define o alvo da forma para a sequência INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Remove o efeito da forma especificada. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Retorna a matriz de efeitos para a forma especificada. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Retorna a matriz de efeitos para o parágrafo especificado. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Retorna a contagem de efeitos para a forma especificada. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Adiciona um novo efeito ao final da sequência. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Adiciona um novo efeito de animação para o parágrafo ao final da sequência. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Adiciona o novo efeito de animação de gráfico para elementos em categoria ou série ao final da sequência. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Retorna o número de efeitos em uma sequência. Somente leitura int.

**Retorna:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Remove o efeito especificado de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efeito a remover. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove um efeito de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do efeito a ser removido int |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os efeitos de uma coleção.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Retorna um efeito no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento. |

**Retorna:**
[IEffect](../../com.aspose.slides/ieffect) - O objeto [IEffect](../../com.aspose.slides/ieffect).
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Retorna ou define o alvo da forma para a sequência INTERACTIVE. Se a sequência não for interativa então retorna null. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Retorna ou define o alvo da forma para a sequência INTERACTIVE. Se a sequência não for interativa então retorna null. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Remove o efeito da forma especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objeto de forma [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Retorna a matriz de efeitos para a forma especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objeto de forma [IShape](../../com.aspose.slides/ishape) |

**Retorna:**
com.aspose.slides.IEffect[] - Array de efeitos [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Retorna a matriz de efeitos para o parágrafo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objeto Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |

**Retorna:**
com.aspose.slides.IEffect[] - Array de efeitos [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Retorna a contagem de efeitos para a forma especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objeto de forma [IShape](../../com.aspose.slides/ishape) |

**Retorna:**
int - Contagem de efeitos int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Adiciona um novo efeito ao final da sequência.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objeto Shape [IShape](../../com.aspose.slides/ishape) para adicionar um efeito |
| effectType | int | Tipo de um efeito de animação [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efeito de animação [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de gatilho do efeito [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retorna:**
[IEffect](../../com.aspose.slides/ieffect) - Novo objeto de efeito [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Adiciona um novo efeito de animação para o parágrafo ao final da sequência.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // selecione o parágrafo para adicionar efeito
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // adicione o efeito de animação Fly ao parágrafo selecionado
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objeto Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Tipo de um efeito de animação [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efeito de animação [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de gatilho do efeito [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retorna:**
[IEffect](../../com.aspose.slides/ieffect) - Novo objeto de efeito [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objeto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo de um efeito de animação [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Índice int |
| effectType | int | Tipo de um efeito de animação [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efeito de animação [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de gatilho do efeito [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retorna:**
[IEffect](../../com.aspose.slides/ieffect) - Novo objeto de efeito [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Adiciona o novo efeito de animação de gráfico para elementos em categoria ou série ao final da sequência.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objeto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo de um efeito de animação [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Índice da série do gráfico int |
| categoriesIndex | int | Índice da categoria int |
| effectType | int | Tipo de um efeito de animação [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efeito de animação [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de gatilho do efeito [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retorna:**
[IEffect](../../com.aspose.slides/ieffect) - Novo objeto de efeito [IEffect](../../com.aspose.slides/ieffect)