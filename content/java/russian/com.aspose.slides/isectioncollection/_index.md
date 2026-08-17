---
title: ISectionCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию секций.
type: docs
url: /ru/com.aspose.slides/isectioncollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Представляет коллекцию секций.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Добавляет новую секцию, начинающуюся с определённого слайда. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Добавляет пустую секцию в указанную позицию коллекции. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Удаляет секцию и слайды, содержащиеся в ней. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Удаляет секцию. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Перемещает секцию и её слайды из коллекции в указанную позицию. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Добавляет пустую секцию в конец коллекции. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Возвращает индекс указанной секции в коллекции. |
| [clear()](#clear--) | Удаляет все секции из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Возвращает элемент по указанному индексу. Только для чтения [ISection](../../com.aspose.slides/isection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Добавляет новую секцию, начинающуюся с определённого слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя секции |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Первый слайд секции |

**Возвращаемое значение:**
[ISection](../../com.aspose.slides/isection) - Добавленная секция.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Добавляет пустую секцию в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя секции |
| index | int | Индекс новой секции. |

**Возвращаемое значение:**
[ISection](../../com.aspose.slides/isection) - Добавленная секция.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Удаляет секцию и слайды, содержащиеся в ней.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Секция, которую необходимо удалить из коллекции. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Удаляет секцию. Слайды, содержащиеся в секции, будут объединены с предыдущей секцией.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Секция, которую необходимо удалить из коллекции. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Перемещает секцию и её слайды из коллекции в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Секция для перемещения. |
| index | int | Целевой индекс. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Добавляет пустую секцию в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя секции |

**Возвращаемое значение:**
[ISection](../../com.aspose.slides/isection) - Добавленная секция.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Возвращает индекс указанной секции в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Секция для поиска. |

**Возвращаемое значение:**
int - Индекс секции или -1, если секция не принадлежит этой коллекции.
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все секции из коллекции.