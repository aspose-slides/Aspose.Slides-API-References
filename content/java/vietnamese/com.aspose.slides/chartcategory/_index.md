---
title: ChartCategory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các danh mục biểu đồ.
type: docs
url: /vi/com.aspose.slides/chartcategory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Biểu diễn các danh mục biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getUseCell()](#getUseCell--) | Nếu true thì thuộc tính AsCell là hiện thực. |
| [getAsCell()](#getAsCell--) | Trả về hoặc đặt đối tượng IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Trả về hoặc đặt đối tượng IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Trả về hoặc đặt đối tượng AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Trả về hoặc đặt đối tượng AsLiteral. |
| [getValue()](#getValue--) | Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Bộ chứa được quản lý cho các giá trị của các mức nhóm danh mục biểu đồ. |
| [remove()](#remove--) | Xóa danh mục khỏi biểu đồ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


Nếu true thì thuộc tính AsCell là hiện thực. Nói cách khác, worksheet được sử dụng để lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa mức). Nếu false thì thuộc tính AsLiteral là hiện thực. Nói cách khác, worksheet KHÔNG được sử dụng để lưu trữ danh mục (và trường hợp này không hỗ trợ danh mục đa mức). Boolean chỉ đọc.

--------------------

Để thay đổi giá trị của thuộc tính này (cho tất cả các danh mục trong bộ sưu tập) đặt giá trị mới cho thuộc tính ChartCategoryCollection.UseCells.

**Trả về:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Trả về hoặc đặt đối tượng IChartDataCell. Nếu danh mục là đa mức thì sử dụng đối tượng IChartDataCell cho mức "0". Đọc/ghi [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Trả về hoặc đặt đối tượng IChartDataCell. Nếu danh mục là đa mức thì sử dụng đối tượng IChartDataCell cho mức "0". Đọc/ghi [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


Trả về hoặc đặt đối tượng AsLiteral. Đọc/ghi Object.

**Trả về:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


Trả về hoặc đặt đối tượng AsLiteral. Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```


Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value. Nếu UseCell là false thì thuộc tính này đại diện cho thuộc tính AsLiteral. Đọc/ghi Object.

**Trả về:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value. Nếu UseCell là false thì thuộc tính này đại diện cho thuộc tính AsLiteral. Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```


Bộ chứa được quản lý cho các giá trị của các mức nhóm danh mục biểu đồ. Danh mục đa mức chứa nhiều hơn một mức nhóm. Chỉ mục các mức nhóm bắt đầu từ 0. Chỉ đọc [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Trả về:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```


Xóa danh mục khỏi biểu đồ.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent\_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject