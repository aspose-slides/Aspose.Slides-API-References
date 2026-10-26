---
title: Sequence
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию эффектов последовательности.
type: docs
url: /ru/com.aspose.slides/sequence/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Представляет последовательность (коллекцию эффектов).
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество эффектов в последовательности. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Удаляет указанный эффект из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет эффект из коллекции. |
| [clear()](#clear--) | Удаляет все эффекты из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает эффект по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [getTriggerShape()](#getTriggerShape--) | Возвращает или задает целевую форму для ИНТЕРАКТИВНОЙ последовательности. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Возвращает или задает целевую форму для ИНТЕРАКТИВНОЙ последовательности. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Удаляет эффект для указанной формы. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Возвращает массив эффектов для указанной формы. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Возвращает массив эффектов для указанного абзаца. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Возвращает количество эффектов для указанной формы. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Добавляет новый эффект в конец последовательности. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Добавляет новый анимационный эффект для абзаца в конец последовательности. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Добавляет новый анимационный эффект диаграммы для категории или серии в конец последовательности. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Добавляет новый анимационный эффект диаграммы для элементов в категории или серии в конец последовательности. |
### getCount() {#getCount--}
```
public final int getCount()
```

Возвращает количество эффектов в последовательности. Только для чтения int.

**Возвращает:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Удаляет указанный эффект из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Элемент, подлежащий удалению. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет эффект из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс эффекта, который необходимо удалить. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет все эффекты из коллекции.
### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Возвращает эффект по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - объект [IEffect](../../com.aspose.slides/ieffect).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Возвращает перечислитель, который перебирает коллекцию.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - java.util.Iterator для всей коллекции.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Возвращает или задает целевую форму для ИНТЕРАКТИВНОЙ последовательности. Если последовательность не интерактивна, возвращает null. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Возвращает или задает целевую форму для ИНТЕРАКТИВНОЙ последовательности. Если последовательность не интерактивна, возвращает null. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Удаляет эффект для указанной формы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Возвращает массив эффектов для указанной формы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Возвращает:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Возвращает массив эффектов для указанного абзаца.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Возвращает:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Возвращает количество эффектов для указанной формы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Возвращает:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Добавляет новый эффект в конец последовательности.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Объект формы [IShape](../../com.aspose.slides/ishape) для добавления эффекта |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтип анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип триггера эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Добавляет новый анимационный эффект для абзаца в конец последовательности.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // выбрать абзац для добавления эффекта
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // добавить анимационный эффект Fly к выбранному абзацу
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Объект абзаца [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтип анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип триггера эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Добавляет новый анимационный эффект диаграммы для категории или серии в конец последовательности.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Объект диаграммы [IChart](../../com.aspose.slides/ichart) |
| type | int | Тип анимационного эффекта [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Индекс int |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтип анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип триггера эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Добавляет новый анимационный эффект диаграммы для элементов в категории или серии в конец последовательности.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Объект диаграммы [IChart](../../com.aspose.slides/ichart) |
| type | int | Тип анимационного эффекта [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Индекс серии диаграммы int |
| categoriesIndex | int | Индекс категории int |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтип анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип триггера эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)