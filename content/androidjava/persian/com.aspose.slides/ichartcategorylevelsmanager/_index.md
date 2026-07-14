---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /fa/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

محفظه مدیریت‌شده مقادیر سطوح دسته‌بندی نمودار.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | شیء IChartDataCell را برای سطح تعریف‌شده برمی‌گرداند. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | آیتم گروه‌بندی را برای سطح تعریف‌شده تنظیم می‌کند. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | آیتم گروه‌بندی را برای سطح تعریف‌شده حذف می‌کند. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

شیء IChartDataCell را برای سطح تعریف‌شده برمی‌گرداند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

آیتم گروه‌بندی را برای سطح تعریف‌شده تنظیم می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | سطح دسته‌بندی به صورت عددی |
| value | java.lang.Object | شیء آیتم گروه‌بندی |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

آیتم گروه‌بندی را برای سطح تعریف‌شده حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | سطح دسته‌بندی به صورت عددی |