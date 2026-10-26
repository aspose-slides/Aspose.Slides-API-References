---
title: ILayoutSlideCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет базовый класс для коллекции слайдов макета.
type: docs
url: /ru/com.aspose.slides/ilayoutslidecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Представляет базовый класс для коллекции слайдов макета.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает слайд макета по индексу. |
| [getByType(byte type)](#getByType-byte-) | Возвращает первый слайд макета указанного типа. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Удаляет макет из коллекции. |
| [removeUnused()](#removeUnused--) | Удаляет неиспользуемые слайды макета (слайды макета, у которых HasDependingSlides равно false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Возвращает слайд макета по индексу. **Только для чтения** [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

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

Возвращает первый слайд макета указанного типа.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | byte | Тип слайда макета для поиска. |

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) с указанным типом или null, если макеты не найдены.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Удаляет макет из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд макета, который нужно удалить из коллекции.

--------------------

1) Чтобы избежать выброса PptxEditException, проверьте свойство HasDependingSlides макета заранее. 2) Вы также можете использовать метод [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) для упрощения кода. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Удаляет неиспользуемые слайды макета (слайды макета, у которых HasDependingSlides равно false).