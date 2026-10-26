---
title: ChartCategoryCollection
second_title: Справочник API Aspose.Slides для Java
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
| [getUseCells()](#getUseCells--) | Если true, то лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Если true, то лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Возвращает количество уровней группировки категорий, использованных. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Если категория существует в коллекции, вернуть её. |
| [add(Object value)](#add-java.lang.Object-) | Создаёт новый [ChartCategory](../../com.aspose.slides/chartcategory) из значения и добавляет его в коллекцию. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Ищет указанный [ChartCategory](../../com.aspose.slides/chartcategory) и возвращает нулевой индекс первого вхождения во всей коллекции. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Удаляет указанное значение. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [size()](#size--) | Возвращает количество элементов в коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к списку (потокобезопасный). |
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

Если true, то лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). Если false, то лист НЕ используется для хранения значений (и этот случай не поддерживает многоуровневые категории). Чтение/запись булево.

**Возвращаемое значение:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Если true, то лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). Если false, то лист НЕ используется для хранения значений (и этот случай не поддерживает многоуровневые категории). Чтение/запись булево.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Возвращает количество уровней группировки категорий, использованных. Для многоуровневых категорий значение больше одного. Только для чтения int.

**Возвращаемое значение:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Если категория существует в коллекции, вернуть её. Иначе создаёт новую категорию диаграммы из [IChartDataCell](../../com.aspose.slides/ichartdatacell) и добавляет её в коллекцию.

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

Этот метод добавляет лист с именем AUTO_DATA и добавляет туда все значения. Если вы используете [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) для добавления или изменения значений ячеек, убедитесь, что вы не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680

**Возвращаемое значение:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Добавленные [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Ищет указанный [ChartCategory](../../com.aspose.slides/chartcategory) и возвращает нулевой индекс первого вхождения во всей коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Категория диаграммы. |

**Возвращаемое значение:**
int - Нулевой индекс первого вхождения значения во всей CollectionBase, если найдено; иначе -1.

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

Удаляет элемент по указанному индексу.

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

Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.

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

Возвращает значение, указывающее, синхронизирован ли доступ к списку (потокобезопасный). Только для чтения булево.

**Возвращаемое значение:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект, который может быть использован для синхронизации доступа к коллекции. Только для чтения Object.

Возвращает корень синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object