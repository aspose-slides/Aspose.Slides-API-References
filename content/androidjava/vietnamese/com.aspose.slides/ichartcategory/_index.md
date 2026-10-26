---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho các danh mục biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Đại diện cho các danh mục biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getUseCell()](#getUseCell--) | Nếu true thì thuộc tính AsCell là thực tế. |
| [getAsCell()](#getAsCell--) | Trả về hoặc đặt đối tượng IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Trả về hoặc đặt đối tượng IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Trả về hoặc đặt AsLiteral nếu UseCell là false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Trả về hoặc đặt AsLiteral nếu UseCell là false. |
| [getValue()](#getValue--) | Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Bộ chứa được quản lý của các giá trị của các mức nhóm danh mục biểu đồ. |
| [remove()](#remove--) | Xóa danh mục khỏi biểu đồ. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Nếu true thì thuộc tính AsCell là thực tế. Nói cách khác, worksheet được sử dụng để lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa cấp). Nếu false thì thuộc tính AsLiteral là thực tế. Nói cách khác, worksheet KHÔNG được sử dụng để lưu trữ danh mục (và trường hợp này không hỗ trợ danh mục đa cấp). Boolean chỉ đọc.

--------------------

Để thay đổi giá trị của thuộc tính này (cho tất cả các danh mục trong bộ sưu tập) đặt giá trị mới cho thuộc tính [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Trả về:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Trả về hoặc đặt đối tượng IChartDataCell. Nếu danh mục là đa cấp thì sử dụng đối tượng IChartDataCell cho mức “0”. Đọc/ghi [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Trả về hoặc đặt đối tượng IChartDataCell. Nếu danh mục là đa cấp thì sử dụng đối tượng IChartDataCell cho mức “0”. Đọc/ghi [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Trả về hoặc đặt AsLiteral nếu UseCell là false. Đọc/ghi Object.

**Trả về:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Trả về hoặc đặt AsLiteral nếu UseCell là false. Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value. Nếu UseCell là false thì thuộc tính này đại diện cho thuộc tính AsLiteral. Đọc/ghi Object.

**Trả về:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value. Nếu UseCell là false thì thuộc tính này đại diện cho thuộc tính AsLiteral. Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Bộ chứa được quản lý của các giá trị của các mức nhóm danh mục biểu đồ. Danh mục đa cấp chứa nhiều hơn một mức nhóm. Chỉ mục mức nhóm bắt đầu từ 0. Chỉ đọc [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Trả về:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Xóa danh mục khỏi biểu đồ.