---
title: IChartSeriesCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию
type: docs
url: /ru/com.aspose.slides/ichartseriescollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Представляет коллекцию [IChartSeries](../../com.aspose.slides/ichartseries)
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [add(int type)](#add-int-) | Создаёт новую серию диаграммы и добавляет её в коллекцию. |
| [insert(int index, int type)](#insert-int-int-) | Создаёт новую серию диаграммы и вставляет её в коллекцию. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Создаёт новую серию диаграммы из [IChartDataCell](../../com.aspose.slides/ichartdatacell) и добавляет её в коллекцию. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Создаёт новую серию диаграммы из [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) и добавляет её в коллекцию. |
| [add(String name, int type)](#add-java.lang.String-int-) | Создаёт новую серию диаграммы из значения и добавляет её в коллекцию. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Ищет указанный [IChartSeries](../../com.aspose.slides/ichartseries) и возвращает нулевой индекс первого вхождения в полной коллекции. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Удаляет указанное значение. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы (включая стиль диаграммы) из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Элемент по указанному индексу.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Создаёт новую серию диаграммы и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип серии |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Новая серия диаграммы.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Создаёт новую серию диаграммы и вставляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс для вставки |
| type | int | Тип диаграммы [ChartType](../../com.aspose.slides/charttype) |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Новая серия диаграммы [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Создаёт новую серию диаграммы из [IChartDataCell](../../com.aspose.slides/ichartdatacell) и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ячейка, содержащая имя серии. |
| type | int | Тип серии

--------------------

Если серия диаграммы уже создана из той же ячейки и находится в коллекции, метод ничего не добавляет и возвращает её индекс. |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Добавленная серия диаграммы или серия, уже находящаяся в коллекции.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Создаёт новую серию диаграммы из [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Ячейки, содержащие имена серий. |
| type | int | Тип серии

--------------------

Если серия диаграммы уже создана из той же ячейки и находится в коллекции, метод ничего не добавляет и возвращает её индекс. |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Добавленная серия диаграммы или серия, уже находящаяся в коллекции.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Создаёт новую серию диаграммы из значения и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя серии. |
| type | int | Тип серии |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Добавленная серия диаграммы.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Ищет указанный [IChartSeries](../../com.aspose.slides/ichartseries) и возвращает нулевой индекс первого вхождения в полной коллекции

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Значение серии диаграммы. |

**Возвращаемое значение:**
int - Нулевой индекс первого вхождения значения в полной CollectionBase, если найдено; иначе, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Удаляет указанное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Значение. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по указанному индексу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс |
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы (включая стиль диаграммы) из коллекции.