---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /fa/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

محفظه‌ای مدیریت‌شده برای مقادیر سطوح دسته‌بندی نمودار.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | یک شیء IChartDataCell را برای سطح تعریف‌شده بازمی‌گرداند. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | مورد گروه‌بندی را برای سطح تعریف‌شده تنظیم می‌کند. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | مورد گروه‌بندی را برای سطح تعریف‌شده حذف می‌کند. |

### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

یک شیء IChartDataCell را برای سطح تعریف‌شده بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| level | int |  |

**مقدار بازگشتی:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

مورد گروه‌بندی را برای سطح تعریف‌شده تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| level | int | سطح دسته‌بندی int |
| value | java.lang.Object | آبجکت مورد گروه‌بندی |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

مورد گروه‌بندی را برای سطح تعریف‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| level | int | سطح دسته‌بندی int |