---
title: ChartCategoryCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn bộ sưu tập của
type: docs
url: /vi/com.aspose.slides/chartcategorycollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Biểu diễn bộ sưu tập của [ChartCategory](../../com.aspose.slides/chartcategory)
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [getUseCells()](#getUseCells--) | Nếu true thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ danh mục đa cấp). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Nếu true thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ danh mục đa cấp). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Trả về số lượng cấp độ nhóm danh mục đã sử dụng. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Nếu danh mục tồn tại trong bộ sưu tập, trả về nó. |
| [add(Object value)](#add-java.lang.Object-) | Tạo mới [ChartCategory](../../com.aspose.slides/chartcategory) từ giá trị và thêm vào bộ sưu tập. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Tìm kiếm [ChartCategory](../../com.aspose.slides/chartcategory) được chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Xóa giá trị được chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã cho. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator để duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [size()](#size--) | Trả về số phần tử trong bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử của bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào List có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một đối tượng có thể được sử dụng để đồng bộ truy cập vào bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Phần tử tại chỉ mục được chỉ định.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Nếu true thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ danh mục đa cấp). Nếu false thì worksheet KHÔNG được sử dụng để lưu trữ các giá trị (và trường hợp này không hỗ trợ danh mục đa cấp). Đọc/ghi boolean.

**Trả về:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Nếu true thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ danh mục đa cấp). Nếu false thì worksheet KHÔNG được sử dụng để lưu trữ các giá trị (và trường hợp này không hỗ trợ danh mục đa cấp). Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Trả về số lượng cấp độ nhóm danh mục đã sử dụng. Lớn hơn một cho các danh mục đa cấp. Chỉ đọc int.

**Trả về:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Nếu danh mục tồn tại trong bộ sưu tập, trả về nó. Nếu không, tạo danh mục biểu đồ mới từ [IChartDataCell](../../com.aspose.slides/ichartdatacell) và thêm vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ô được sử dụng để tạo danh mục biểu đồ. |

**Trả về:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Đã thêm hoặc danh mục đã tồn tại.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Tạo mới [ChartCategory](../../com.aspose.slides/chartcategory) từ giá trị và thêm vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object | Giá trị.

--------------------

Phương pháp này thêm worksheet có tên AUTO_DATA và thêm tất cả các giá trị vào đó. Nếu bạn sử dụng [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) để thêm hoặc chỉnh sửa giá trị ô, hãy chắc chắn rằng bạn không sử dụng worksheet này. Số lượng tối đa các giá trị được thêm bằng phương pháp này không được vượt quá 16711680 |

**Trả về:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Đã thêm [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Tìm kiếm [ChartCategory](../../com.aspose.slides/chartcategory) được chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Danh mục biểu đồ. |

**Trả về:**
int - Chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của giá trị trong toàn bộ CollectionBase, nếu tìm thấy; nếu không, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Xóa giá trị được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Giá trị. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của danh mục cần xóa. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Trả về một enumerator để duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### size() {#size--}
```
public final int size()
```

Trả về số phần tử trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử của bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào List có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một đối tượng có thể được sử dụng để đồng bộ truy cập vào bộ sưu tập. Chỉ đọc Object.

Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**
java.lang.Object