---
title: IChartCategoryCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho tập hợp của
type: docs
url: /vi/com.aspose.slides/ichartcategorycollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Represents collection of [IChartCategory](../../com.aspose.slides/ichartcategory)
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [getUseCells()](#getUseCells--) | Nếu true thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ các danh mục đa cấp). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Nếu true thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ các danh mục đa cấp). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Trả về số lượng mức nhóm danh mục đã sử dụng. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Nếu danh mục tồn tại trong tập hợp, trả về nó. |
| [add(Object value)](#add-java.lang.Object-) | Tạo mới [IChartCategory](../../com.aspose.slides/ichartcategory) từ giá trị và thêm vào tập hợp. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Tìm kiếm [IChartCategory](../../com.aspose.slides/ichartcategory) được chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Xóa giá trị được chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã cho. |
| [clear()](#clear--) | Xóa tất cả phần tử khỏi tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Phần tử tại chỉ mục được chỉ định.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Nếu true thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ các danh mục đa cấp). Nếu false thì worksheet KHÔNG được sử dụng để lưu trữ giá trị (và trường hợp này không hỗ trợ các danh mục đa cấp). boolean có thể đọc/ghi.

**Returns:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Nếu true thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ các danh mục đa cấp). Nếu false thì worksheet KHÔNG được sử dụng để lưu trữ giá trị (và trường hợp này không hỗ trợ các danh mục đa cấp). boolean có thể đọc/ghi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Trả về số lượng mức nhóm danh mục đã sử dụng. Có hơn một mức cho các danh mục đa cấp. int chỉ đọc.

**Returns:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Nếu danh mục tồn tại trong tập hợp, trả về nó. Nếu không, tạo mới danh mục biểu đồ từ [IChartDataCell](../../com.aspose.slides/ichartdatacell) và thêm vào tập hợp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ô được sử dụng để tạo danh mục biểu đồ. |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Đã thêm hoặc danh mục đã tồn tại.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Tạo mới [IChartCategory](../../com.aspose.slides/ichartcategory) từ giá trị và thêm vào tập hợp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Giá trị.

--------------------

Phương pháp này thêm worksheet có tên AUTO_DATA và thêm tất cả các giá trị vào đó. Nếu bạn sử dụng [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) để thêm hoặc chỉnh sửa giá trị ô, hãy chắc chắn rằng bạn không sử dụng worksheet này. Số lượng giá trị tối đa được thêm bằng phương pháp này không được vượt quá 16711680

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Đã thêm [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Tìm kiếm [IChartCategory](../../com.aspose.slides/ichartcategory) được chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Danh mục biểu đồ. |

**Returns:**
int - Chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của giá trị trong toàn bộ CollectionBase, nếu tìm thấy; nếu không, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Xóa giá trị được chỉ định.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Giá trị. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã cho.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục của danh mục cần xóa. |
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả phần tử khỏi tập hợp.