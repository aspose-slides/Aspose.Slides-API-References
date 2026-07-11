---
title: ChartCategoryCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию
type: docs
url: /ru/com.aspose.slides/chartcategorycollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Представляет коллекцию [ChartCategory](../../com.aspose.slides/chartcategory)
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getUseCells()](#getUseCells--) | Если true, лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Если true, лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Возвращает количество уровней группировки категорий. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Если категория существует в коллекции, возвращает её. |
| [add(Object value)](#add-java.lang.Object-) | Создаёт новый [ChartCategory](../../com.aspose.slides/chartcategory) из значения и добавляет его в коллекцию. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Ищет указанный [ChartCategory](../../com.aspose.slides/chartcategory) и возвращает нулевой индекс первого вхождения во всей Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Удаляет указанное значение. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по заданному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [size()](#size--) | Возвращает количество элементов в коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к List (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект, который можно использовать для синхронизации доступа к коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Элемент по указанному индексу.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Если true, лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). Если false, лист НЕ используется для хранения значений (и в этом случае не поддерживаются многоуровневые категории). Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Если true, лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). Если false, лист НЕ используется для хранения значений (и в этом случае не поддерживаются многоуровневые категории). Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Возвращает количество уровней группировки категорий. Больше одного для многоуровневых категорий. Только для чтения int.

**Возвращаемое значение:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Если категория существует в коллекции, возвращает её. Иначе создаёт новую категорию диаграммы из [IChartDataCell](../../com.aspose.slides/ichartdatacell) и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ячейка, используемая для создания категории диаграммы. |

**Возвращаемое значение:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Добавленная или существующая категория.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Создаёт новый [ChartCategory](../../com.aspose.slides/chartcategory) из значения и добавляет его в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object | Значение.

--------------------

Этот метод добавляет лист с именем AUTO_DATA и помещает туда все значения. Если вы используете [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) для добавления или редактирования значений ячеек, убедитесь, что не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680

**Возвращаемое значение:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Добавлен [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Ищет указанный [ChartCategory](../../com.aspose.slides/chartcategory) и возвращает нулевой индекс первого вхождения во всей Collection.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Категория диаграммы. |

**Возвращаемое значение:**
int - Нулевой индекс первого вхождения значения во всей CollectionBase, если найден; иначе -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Удаляет указанное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Значение. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс категории для удаления. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы из коллекции.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Возвращает перечислитель, который перебирает коллекцию.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - java.util.Iterator для всей коллекции.
### size() {#size--}
```
public final int size()
```

Возвращает количество элементов в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к List (потокобезопасен). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект, который можно использовать для синхронизации доступа к коллекции. Только для чтения Object.
Возвращает корень синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object