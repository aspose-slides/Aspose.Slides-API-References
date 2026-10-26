---
title: MasterSlideCollection
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет коллекцию мастер-слайдов.
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

Представляет коллекцию мастеров слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Получает фактическое количество элементов, содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Удаляет первое вхождение указанного объекта из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Удаляет неиспользуемые мастера слайдов. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Добавляет копию указанного мастера слайда в конец коллекции. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Вставляет копию указанного мастера слайда в указанную позицию коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### size() {#size--}
```
public final int size()
```

Получает фактическое количество элементов, содержащихся в коллекции. **Только для чтения** int.

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Получает элемент по указанному индексу. **Только для чтения** [MasterSlide](../../com.aspose.slides/masterslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Удаляет первое вхождение указанного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Слайд-мастер, который нужно удалить из коллекции. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |

--------------------

Чтобы избежать выбрасывания PptxEditException, проверьте свойство HasDependingSlides мастера заранее. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Удаляет неиспользуемые мастера слайдов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ignorePreserveField | boolean | Определяет, следует ли удалять неиспользуемый мастер, даже если его свойства [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) установлены в true. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Добавляет копию указанного мастера слайда в конец коллекции. Связанные слайд-макеты также будут скопированы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Слайд для клонирования. |

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Добавленный слайд.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Вставляет копию указанного мастера слайда в указанную позицию коллекции. Связанные слайд-макеты также будут скопированы.

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Создать экземпляр класса Presentation для загрузки исходного файла презентации
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Создать экземпляр класса Presentation для целевой презентации (в которую будет клонирован слайд)
>      Presentation destPres = new Presentation();
>      try {
>          // Создать экземпляр ISlide из коллекции слайдов в исходной презентации вместе с
>          // Мастер-слайдом
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Получить мастер-слайды целевой презентации
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Клонировать нужный мастер-слайд из исходной презентации в коллекцию мастеров в
>          // Целевой презентации
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Коллекция слайдов в целевой презентации
>          ISlideCollection slds = destPres.getSlides();
>          // Клонировать исходный слайд в коллекцию слайдов целевой презентации.
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

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Вставленный мастер-слайд.
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

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). **Только для чтения** boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает корень синхронизации. **Только для чтения** Object.

**Возвращаемое значение:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Перечислитель, который можно использовать для обхода коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - java.util.Iterator для всей коллекции.