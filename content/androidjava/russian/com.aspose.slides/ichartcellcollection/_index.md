---
title: IChartCellCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию ячеек с данными.
type: docs
url: /ru/com.aspose.slides/ichartcellcollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Представляет коллекцию ячеек с данными.
## Методы

| Метод | Описание |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Возвращает адрес набора ячеек в рабочей книге. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Конкатенированная строка из всех строковых значений ячеек. |
| [get_Item(int index)](#get-Item-int-) | Возвращает ячейку (IChartDataCell) по индексу. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Добавляет новую ячейку в коллекцию. |
| [add(Object value)](#add-java.lang.Object-) | Создаёт [IChartDataCell](../../com.aspose.slides/ichartdatacell) из указанного значения и добавляет его в коллекцию. |
| [removeAt(int index)](#removeAt-int-) | Удаляет ячейку из коллекции по индексу. |
| [getCount()](#getCount--) | Получает количество ячеек в коллекции. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

Возвращает адрес набора ячеек в рабочей книге.

**Возвращаемое значение:**
java.lang.String - Адрес набора ячеек в рабочей книге String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

Конкатенированная строка из всех строковых значений ячеек.

**Возвращаемое значение:**
java.lang.String - Полученная строка String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

Возвращает ячейку (IChartDataCell) по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс ячейки. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Ячейка с данными.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

Добавляет новую ячейку в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Новая ячейка для добавления. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

Создаёт [IChartDataCell](../../com.aspose.slides/ichartdatacell) из указанного значения и добавляет его в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object | Значение. |

---

Этот метод добавляет лист с именем AUTO_DATA и помещает туда все значения. Если вы используете [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) для добавления или редактирования значений ячеек, убедитесь, что не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет ячейку из коллекции по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс ячейки для удаления. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Получает количество ячеек в коллекции. Только для чтения int.

**Возвращаемое значение:**
int