---
title: ITextAnimationCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию текстовых анимаций.
type: docs
url: /ru/com.aspose.slides/itextanimationcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Представляет коллекцию текстовых анимаций.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по индексу. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Возвращает все элементы |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Возвращает элемент по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Возвращает все элементы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) элемент. |

**Возвращаемое значение:**
com.aspose.slides.ITextAnimation[] - Массив [ITextAnimation](../../com.aspose.slides/itextanimation)