---
title: MasterSlideCollection
second_title: Aspose.Slides для Java справочник API
description: Представляет коллекцию основных слайдов.
type: docs
url: /ru/com.aspose.slides/masterslidecollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Представляет коллекцию основных слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество элементов, фактически содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Удаляет первое вхождение указанного объекта из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Удаляет неиспользуемые основные слайды. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Добавляет копию указанного основного слайда в конец коллекции. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Вставляет копию указанного основного слайда в заданную позицию коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который итерирует коллекцию. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### size() {#size--}
```
public final int size()
```


Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращает:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Возвращает элемент по указанному индексу. Только для чтения [MasterSlide](../../com.aspose.slides/masterslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Удаляет первое вхождение указанного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Основной слайд, который нужно удалить из коллекции. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой базовый индекс элемента, который нужно удалить. |

--------------------

Чтобы избежать выброса PptxEditException, проверьте свойство HasDependingSlides у мастера заранее. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Удаляет неиспользуемые основные слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ignorePreserveField | boolean | Определяет, следует ли этому методу удалять неиспользуемый мастер, даже если его свойство [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) установлено в true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Добавляет копию указанного основного слайда в конец коллекции. Связанные макетные слайды также будут скопированы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Слайд для клонирования. |

**Возвращает:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Добавленный слайд.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Вставляет копию указанного основного слайда в указанную позицию коллекции. Связанные макетные слайды также будут скопированы.

> ```
> Следующий пример показывает, как клонировать основной слайд в другую презентацию PowerPoint.
>  
>  // Создайте экземпляр класса Presentation для загрузки исходного файла презентации
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Создайте экземпляр класса Presentation для целевой презентации (куда будет клонирован слайд)
>      Presentation destPres = new Presentation();
>      try {
>          // Создайте экземпляр ISlide из коллекции слайдов исходной презентации вместе с
>          // Основным слайдом
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Получить основные слайды целевой презентации
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Клонировать нужный основной слайд из исходной презентации в коллекцию основных слайдов в
>          // Целевой презентации
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Коллекция слайдов в целевой презентации
>          ISlideCollection slds = destPres.getSlides();
>          // Клонировать исходный слайд в коллекцию слайдов назначения.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Сохранить целевую презентацию на диск
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Слайд для клонирования. |

**Возвращает:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Вставленный основной слайд.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает объект синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


Возвращает перечислитель, который итерирует коллекцию.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Перечислитель, который можно использовать для итерации по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - java.util.Iterator для всей коллекции.