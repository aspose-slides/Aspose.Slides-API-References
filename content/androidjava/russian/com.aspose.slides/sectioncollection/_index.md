---
title: SectionCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию разделов.
type: docs
url: /ru/com.aspose.slides/sectioncollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Представляет коллекцию разделов.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Добавляет раздел слайдов, начавшийся с указанного слайда. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Добавляет пустой раздел в конец коллекции. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Добавляет пустой раздел в указанную позицию коллекции. |
| [size()](#size--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Возвращает индекс указанного раздела в коллекции. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Удаляет раздел и слайды, содержащиеся в разделе. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Удаляет раздел. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Перемещает раздел и его слайды из коллекции в указанную позицию. |
| [clear()](#clear--) | Удаляет все разделы из коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует всю коллекцию в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```


Получает элемент по указанному индексу. Только для чтения [ISection](../../com.aspose.slides/isection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возврат:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```


Добавляет раздел слайдов, начавшийся с конкретного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя раздела |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Первый слайд раздела |

**Возврат:**
[ISection](../../com.aspose.slides/isection) - Добавленный раздел.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```


Добавляет пустой раздел в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя раздела |

**Возврат:**
[ISection](../../com.aspose.slides/isection) - Добавленный раздел.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```


Добавляет пустой раздел в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя раздела |
| index | int | Индекс нового раздела. |

**Возврат:**
[ISection](../../com.aspose.slides/isection) - Добавленный раздел.
### size() {#size--}
```
public final int size()
```


Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возврат:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```


Возвращает индекс указанного раздела в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для поиска. |

**Возврат:**
int - Индекс раздела или -1, если раздел не из этой коллекции.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```


Удаляет раздел и слайды, содержащиеся в разделе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел, который нужно удалить из коллекции. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```


Удаляет раздел. Слайды, содержащиеся в разделе, будут объединены с предыдущим разделом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел, который нужно удалить из коллекции. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```


Перемещает раздел и его слайды из коллекции в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для перемещения. |
| index | int | Целевой индекс. |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все разделы из коллекции.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Копирует всю коллекцию в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив |
| index | int | Индекс в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возврат:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает объект синхронизации. Только для чтения Object.

**Возврат:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```


Возвращает перечислитель, который перебирает элементы коллекции.

**Возврат:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возврат:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - java.util.Iterator для всей коллекции.