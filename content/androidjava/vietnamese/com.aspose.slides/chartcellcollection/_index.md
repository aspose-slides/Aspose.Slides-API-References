---
title: ChartCellCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho một tập hợp các ô có dữ liệu.
type: docs
url: /vi/com.aspose.slides/chartcellcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Đại diện cho một tập hợp các ô có dữ liệu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Trả về địa chỉ của tập hợp các ô trong sổ làm việc. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Chuỗi nối từ tất cả các giá trị chuỗi của các ô. |
| [get_Item(int index)](#get-Item-int-) | Trả về một ô (IChartDataCell) theo chỉ mục. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Thêm ô mới vào tập hợp. |
| [add(Object value)](#add-java.lang.Object-) | Tạo [ChartDataCell](../../com.aspose.slides/chartdatacell) từ giá trị được chỉ định và thêm nó vào tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa một ô khỏi tập hợp theo chỉ mục. |
| [getCount()](#getCount--) | Lấy số lượng ô trong tập hợp. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ tập hợp. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Trả về địa chỉ của tập hợp các ô trong sổ làm việc.

**Trả về:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Chuỗi nối từ tất cả các giá trị chuỗi của các ô.

**Trả về:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


Trả về một ô (IChartDataCell) theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một ô. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Ô có dữ liệu.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Thêm ô mới vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ô mới để thêm. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Tạo [ChartDataCell](../../com.aspose.slides/chartdatacell) từ giá trị được chỉ định và thêm nó vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object | Giá trị.

--------------------

Phương thức này thêm một worksheet có tên AUTO_DATA và thêm tất cả các giá trị vào đó. Nếu bạn sử dụng [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) để thêm hoặc chỉnh sửa giá trị Cell, hãy đảm bảo rằng bạn không sử dụng worksheet này. Số lượng tối đa các giá trị được thêm bằng phương thức này không được vượt quá 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa một ô khỏi tập hợp theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của ô cần xóa. |
### getCount() {#getCount--}
```
public final int getCount()
```


Lấy số lượng ô trong tập hợp. Chỉ đọc int.

**Trả về:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Trả về một enumerator cho phép duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Một IGenericEnumerator có thể được sử dụng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Trả về một iterator java cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Một java.util.Iterator cho toàn bộ tập hợp.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject