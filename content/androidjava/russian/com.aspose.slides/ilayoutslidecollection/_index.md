---
title: ILayoutSlideCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет базовый класс для коллекции слайдов-шаблонов.
type: docs
url: /ru/com.aspose.slides/ilayoutslidecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Представляет базовый класс для коллекции слайдов-шаблонов.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает слайд-шаблон по индексу. |
| [getByType(byte type)](#getByType-byte-) | Возвращает первый слайд-шаблон указанного типа. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Удаляет шаблон из коллекции. |
| [removeUnused()](#removeUnused--) | Удаляет неиспользуемые слайды-шаблоны (слайды-шаблоны, у которых HasDependingSlides = false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Возвращает слайд-шаблон по индексу. Только для чтения [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Возвращает первый слайд-шаблон указанного типа.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | byte | Тип слайда-шаблона для поиска. |

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) с указанным типом или null, если шаблоны не найдены.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Удаляет шаблон из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд-шаблон, который необходимо удалить из коллекции.

--------------------

1) Чтобы избежать возникновения PptxEditException, проверьте свойство HasDependingSlides шаблона заранее. 2) Вы также можете использовать метод [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) для упрощения кода. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Удаляет неиспользуемые слайды-шаблоны (слайды-шаблоны, у которых HasDependingSlides = false).