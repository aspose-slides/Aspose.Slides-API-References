---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides для Android через справочник Java API
description: Управляемый контейнер значений уровней категорий диаграммы.
type: docs
url: /ru/com.aspose.slides/chartcategorylevelsmanager/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

Управляемый контейнер значений уровней категорий диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Возвращает объект IChartDataCell для указанного уровня. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Устанавливает элемент группировки для указанного уровня. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Удаляет элемент группировки для указанного уровня. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

Возвращает объект IChartDataCell для указанного уровня.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int |  |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```

Устанавливает элемент группировки для указанного уровня.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

Удаляет элемент группировки для указанного уровня.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int |  |