---
title: ISequence
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию последовательности эффектов.
type: docs
url: /ru/com.aspose.slides/isequence/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Представляет последовательность (коллекцию эффектов).

## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество эффектов в последовательности. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Удаляет указанный эффект из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет эффект из коллекции. |
| [clear()](#clear--) | Удаляет все эффекты из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает эффект по заданному индексу. |
| [getTriggerShape()](#getTriggerShape--) | Возвращает или задает целевую форму для последовательности INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Возвращает или задает целевую форму для последовательности INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Удалить эффект для указанной формы. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Возвращает массив эффектов для указанной формы. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Возвращает массив эффектов для указанного абзаца. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Возвращает количество эффектов для указанной формы. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Добавить новый эффект в конец последовательности. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Добавить новый анимационный эффект для абзаца в конец последовательности. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Добавляет новый анимационный эффект диаграммы для категории или серии в конец последовательности. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Добавляет новый анимационный эффект диаграммы для элементов в категории или серии в конец последовательности. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Возвращает количество эффектов в последовательности. Только для чтения int.

**Возвращает:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Удаляет указанный эффект из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Эффект для удаления. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет эффект из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс эффекта для удаления int |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все эффекты из коллекции.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Возвращает эффект по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - объект [IEffect](../../com.aspose.slides/ieffect).

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Возвращает или задает целевую форму для последовательности INTERACTIVE. Если последовательность не интерактивна, возвращает null. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Возвращает или задает целевую форму для последовательности INTERACTIVE. Если последовательность не интерактивна, возвращает null. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Удалить эффект для указанной формы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Объект формы [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Возвращает массив эффектов для указанной формы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Объект формы [IShape](../../com.aspose.slides/ishape) |

**Возвращает:**
com.aspose.slides.IEffect[] - массив эффектов [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Возвращает массив эффектов для указанного абзаца.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Объект абзаца [IParagraph](../../com.aspose.slides/iparagraph) |

**Возвращает:**
com.aspose.slides.IEffect[] - массив эффектов [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Возвращает количество эффектов для указанной формы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Объект формы [IShape](../../com.aspose.slides/ishape) |

**Возвращает:**
int - количество эффектов int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Добавить новый эффект в конец последовательности.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Объект формы [IShape](../../com.aspose.slides/ishape) для добавления эффекта |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтипы анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип срабатывания эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Добавить новый анимационный эффект для абзаца в конец последовательности.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // выберите абзац для добавления эффекта
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // добавить эффект анимации Fly к выбранному абзацу
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Объект абзаца [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтипы анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип срабатывания эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Добавляет новый анимационный эффект диаграммы для категории или серии в конец последовательности.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Объект диаграммы [IChart](../../com.aspose.slides/ichart) |
| type | int | Тип анимационного эффекта [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Индекс int |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтипы анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип срабатывания эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
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
| subtype | int | Подтипы анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип срабатывания эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращает:**
[IEffect](../../com.aspose.slides/ieffect) - новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)