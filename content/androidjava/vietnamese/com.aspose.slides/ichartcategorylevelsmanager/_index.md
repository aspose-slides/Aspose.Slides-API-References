---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Container quản lý các giá trị của các cấp độ danh mục biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Container quản lý các giá trị của các cấp độ danh mục biểu đồ.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Trả về đối tượng IChartDataCell cho cấp độ đã định. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Đặt mục nhóm cho cấp độ đã định. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Xóa mục nhóm cho cấp độ đã định. |

### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Trả về đối tượng IChartDataCell cho cấp độ đã định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| level | int |  |

**Giá trị trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Đặt mục nhóm cho cấp độ đã định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| level | int | Cấp độ danh mục int |
| value | java.lang.Object | Đối tượng mục nhóm |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Xóa mục nhóm cho cấp độ đã định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| level | int | Cấp độ danh mục int |