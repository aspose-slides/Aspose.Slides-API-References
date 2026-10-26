---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /ru/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
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
public abstract IChartDataCell get_Item(int level)
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
public abstract void setGroupingItem(int level, Object value)
```

Устанавливает элемент группировки для указанного уровня.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int | Уровень категории int |
| value | java.lang.Object | Объект элемента группировки |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Удаляет элемент группировки для указанного уровня.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int | Уровень категории int |