---
title: IChartCategoryCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn bộ sưu tập của
type: docs
url: /vi/com.aspose.slides/ichartcategorycollection/
---
**Tất cả các giao diện được thực thi:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Biểu diễn bộ sưu tập của [IChartCategory](../../com.aspose.slides/ichartcategory)
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [getUseCells()](#getUseCells--) | Nếu true thì worksheet được dùng để lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa cấp). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Nếu true thì worksheet được dùng để lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa cấp). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Trả về số lượng cấp nhóm danh mục đã sử dụng. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Nếu danh mục tồn tại trong bộ sưu tập, trả về nó. |
| [add(Object value)](#add-java.lang.Object-) | Tạo mới [IChartCategory](../../com.aspose.slides/ichartcategory) từ giá trị và thêm vào bộ sưu tập. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Tìm kiếm [IChartCategory](../../com.aspose.slides/ichartcategory) được chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Xóa giá trị được chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã cho. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Phần tử tại chỉ mục đã chỉ định.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Nếu true thì worksheet được dùng để lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa cấp). Nếu false thì worksheet KHÔNG được dùng để lưu trữ giá trị (và trường hợp này không hỗ trợ danh mục đa cấp). Boolean đọc/ghi.

**Trả về:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Nếu true thì worksheet được dùng để lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa cấp). Nếu false thì worksheet KHÔNG được dùng để lưu trữ giá trị (và trường hợp này không hỗ trợ danh mục đa cấp). Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Trả về số lượng cấp nhóm danh mục đã sử dụng. Lớn hơn một cho danh mục đa cấp. int chỉ đọc.

**Trả về:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Nếu danh mục tồn tại trong bộ sưu tập, trả về nó. Nếu không, tạo mới chart category từ [IChartDataCell](../../com.aspose.slides/ichartdatacell) và thêm vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell used to create chart category. |

**Trả về:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Danh mục đã thêm hoặc đã tồn tại.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Tạo mới [IChartCategory](../../com.aspose.slides/ichartcategory) từ giá trị và thêm vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object | Giá trị.

--------------------

Phương thức này thêm worksheet với tên AUTO_DATA và thêm tất cả các giá trị vào đó. Nếu bạn sử dụng [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) để thêm hoặc chỉnh sửa giá trị ô, hãy chắc chắn rằng bạn không sử dụng worksheet này. Số lượng giá trị tối đa có thể được thêm bằng phương thức này không được vượt quá 16711680 |

**Trả về:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Đã thêm [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Tìm kiếm [IChartCategory](../../com.aspose.slides/ichartcategory) được chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Chart category. |

**Trả về:**
int - Chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của giá trị trong toàn bộ CollectionBase, nếu tìm thấy; nếu không, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Xóa giá trị được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Giá trị. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của danh mục cần xóa. |
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.