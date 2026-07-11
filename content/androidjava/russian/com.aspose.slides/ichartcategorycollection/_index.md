---
title: IChartCategoryCollection
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет коллекцию
type: docs
url: /ru/com.aspose.slides/ichartcategorycollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Представляет коллекцию [IChartCategory](../../com.aspose.slides/ichartcategory)
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getUseCells()](#getUseCells--) | Если true, то рабочий лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Если true, то рабочий лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Возвращает количество уровней группировки категорий, используемых. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Если категория существует в коллекции, возвращает её. |
| [add(Object value)](#add-java.lang.Object-) | Создаёт новый [IChartCategory](../../com.aspose.slides/ichartcategory) из значения и добавляет его в коллекцию. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Ищет указанный [IChartCategory](../../com.aspose.slides/ichartcategory) и возвращает нулевой индекс первого вхождения во всей Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Удаляет указанное значение. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по заданному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возврат:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Элемент по указанному индексу.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Если true, то рабочий лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). Если false, то рабочий лист НЕ используется для хранения значений (и в этом случае не поддерживаются многоуровневые категории). Чтение/запись, булево.

**Возврат:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Если true, то рабочий лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). Если false, то рабочий лист НЕ используется для хранения значений (и в этом случае не поддерживаются многоуровневые категории). Чтение/запись, булево.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Возвращает количество уровней группировки категорий, используемых. Больше одного для многоуровневых категорий. Только для чтения, тип int.

**Возврат:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Если категория существует в коллекции, возвращает её. Иначе создаёт новую категорию диаграммы из [IChartDataCell](../../com.aspose.slides/ichartdatacell) и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ячейка, используемая для создания категории диаграммы. |

**Возврат:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Добавленная или существующая категория.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Создаёт новый [IChartCategory](../../com.aspose.slides/ichartcategory) из значения и добавляет его в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object | Значение.

--------------------

Этот метод добавляет рабочий лист с именем AUTO_DATA и добавляет все значения туда. Если вы используете [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) для добавления или редактирования значений ячеек, убедитесь, что вы не используете этот рабочий лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680

**Возврат:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Добавлен [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Ищет указанный [IChartCategory](../../com.aspose.slides/ichartcategory) и возвращает нулевой индекс первого вхождения во всей Collection

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Категория диаграммы. |

**Возврат:**
int - Нулевой индекс первого вхождения значения во всей CollectionBase, если найдено; иначе -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Удаляет указанное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Значение. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс категории для удаления. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы из коллекции.