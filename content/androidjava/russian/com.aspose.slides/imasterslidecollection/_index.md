---
title: IMasterSlideCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию мастер-слайдов.
type: docs
url: /ru/com.aspose.slides/imasterslidecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Представляет коллекцию мастер-слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Удаляет неиспользуемые мастер-слайды. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Добавляет копию указанного мастер-слайда в конец коллекции. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Вставляет копию указанного мастер-слайда в указанную позицию коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IMasterSlide](../../com.aspose.slides/imasterslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Удаляет первое вхождение конкретного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-слайд, который нужно удалить из коллекции. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Удаляет неиспользуемые мастер-слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ignorePreserveField | boolean | Определяет, должно ли этот метод удалять неиспользуемый мастер, даже если его [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) property установлен в true. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Добавляет копию указанного мастер-слайда в конец коллекции. Связанные слайды макета также будут скопированы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Слайд для клонирования. |

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Добавленный слайд.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Вставляет копию указанного мастер-слайда в указанную позицию коллекции. Связанные слайды макета также будут скопированы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Слайд для клонирования. |

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Вставленный мастер-слайд.