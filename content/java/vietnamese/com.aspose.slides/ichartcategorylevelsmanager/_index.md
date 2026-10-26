---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides cho Java Tham khảo API
description: Bộ chứa được quản lý của các giá trị mức danh mục biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Bộ chứa được quản lý của các giá trị mức danh mục biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Trả về đối tượng IChartDataCell cho mức đã định nghĩa. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Đặt mục nhóm cho mức đã định nghĩa. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Xóa mục nhóm cho mức đã định nghĩa. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```


Trả về đối tượng IChartDataCell cho mức đã định nghĩa.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| level | int |  |

**Kết quả trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```


Đặt mục nhóm cho mức đã định nghĩa.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| level | int | Mức danh mục int |
| value | java.lang.Object | Đối tượng mục nhóm |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


Xóa mục nhóm cho mức đã định nghĩa.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| level | int | Mức danh mục int |