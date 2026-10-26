---
title: ISectionCollection
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет коллекцию разделов.
type: docs
url: /ru/com.aspose.slides/isectioncollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Представляет коллекцию разделов.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Добавляет новый раздел, начинающийся с конкретного слайда. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Добавляет пустой раздел в указанную позицию коллекции. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Удаляет раздел и слайды, содержащиеся в разделе. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Удаляет раздел. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Перемещает раздел и его слайды из коллекции в указанную позицию. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Добавляет пустой раздел в конец коллекции. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Возвращает индекс указанного раздела в коллекции. |
| [clear()](#clear--) | Удаляет все разделы из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [ISection](../../com.aspose.slides/isection).

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

Добавляет новый раздел, начинающийся с конкретного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя раздела |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Первый слайд раздела |

**Возвращаемое значение:**
[ISection](../../com.aspose.slides/isection) - Добавленный раздел.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Добавляет пустой раздел в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя раздела |
| index | int | Индекс нового раздела. |

**Возвращаемое значение:**
[ISection](../../com.aspose.slides/isection) - Добавленный раздел.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Удаляет раздел и слайды, содержащиеся в разделе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для удаления из коллекции. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Удаляет раздел. Слайды, содержащиеся в разделе, будут объединены с предыдущим разделом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для удаления из коллекции. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Перемещает раздел и его слайды из коллекции в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для перемещения. |
| index | int | Целевой индекс. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Добавляет пустой раздел в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя раздела |

**Возвращаемое значение:**
[ISection](../../com.aspose.slides/isection) - Добавленный раздел.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Возвращает индекс указанного раздела в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для поиска. |

**Возвращаемое значение:**
int - Индекс раздела или -1, если раздел не принадлежит этой коллекции.
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все разделы из коллекции.