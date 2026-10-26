---
title: ChartSeriesCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn bộ sưu tập của
type: docs
url: /vi/com.aspose.slides/chartseriescollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Biểu diễn bộ sưu tập của [ChartSeries](../../com.aspose.slides/chartseries)
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại vị trí chỉ định. |
| [size()](#size--) | Trả về số lượng đối tượng trong bộ sưu tập. |
| [add(int type)](#add-int-) | Tạo series biểu đồ mới và thêm nó vào bộ sưu tập. |
| [insert(int index, int type)](#insert-int-int-) | Tạo series biểu đồ mới và chèn nó vào bộ sưu tập. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Tạo series biểu đồ mới từ [ChartDataCell](../../com.aspose.slides/chartdatacell) và thêm nó vào bộ sưu tập. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Tạo series biểu đồ mới từ [ChartCellCollection](../../com.aspose.slides/chartcellcollection) và thêm nó vào bộ sưu tập. |
| [add(String name, int type)](#add-java.lang.String-int-) | Tạo series biểu đồ mới từ giá trị và thêm nó vào bộ sưu tập. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Tìm kiếm [ChartSeries](../../com.aspose.slides/chartseries) được chỉ định và trả về chỉ số bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Xóa giá trị được chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa một điều khiển ActiveX được lưu tại vị trí chỉ định khỏi bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các điều khiển khỏi bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép toàn bộ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


Lấy phần tử tại vị trí chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Phần tử tại vị trí chỉ định.
### size() {#size--}
```
public final int size()
```


Trả về số lượng đối tượng trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```


Tạo series biểu đồ mới và thêm nó vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại series |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Series biểu đồ mới.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```


Tạo series biểu đồ mới và chèn nó vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


Tạo series biểu đồ mới từ [ChartDataCell](../../com.aspose.slides/chartdatacell) và thêm nó vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ô chứa tên series. |
| type | int | Loại thiết lập cho series

--------------------

Nếu series biểu đồ được tạo từ cùng một ô đã có trong bộ sưu tập thì phương thức không thêm gì và trả về chỉ mục của nó. |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Series biểu đồ đã thêm hoặc series đã có trong bộ sưu tập.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


Tạo series biểu đồ mới từ [ChartCellCollection](../../com.aspose.slides/chartcellcollection) và thêm nó vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Các ô chứa tên series. |
| type | int | Loại thiết lập cho series

--------------------

Nếu series biểu đồ được tạo từ cùng một ô đã có trong bộ sưu tập thì phương thức không thêm gì và trả về chỉ mục của nó. |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Series biểu đồ đã thêm hoặc series đã có trong bộ sưu tập.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```


Tạo series biểu đồ mới từ giá trị và thêm nó vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên series. |
| type | int | Loại thiết lập cho series |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Series biểu đồ đã thêm.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```


Tìm kiếm [ChartSeries](../../com.aspose.slides/chartseries) được chỉ định và trả về chỉ số bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Giá trị series biểu đồ. |

**Trả về:**
int - Chỉ số bắt đầu từ 0 của lần xuất hiện đầu tiên của giá trị trong toàn bộ CollectionBase, nếu tìm thấy; nếu không, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```


Xóa giá trị được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Giá trị. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa một điều khiển ActiveX được lưu tại vị trí chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của điều khiển cần xóa. |
### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các điều khiển khỏi bộ sưu tập.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép toàn bộ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích |
| index | int | Chỉ số trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị cho biết liệu việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**
java.lang.Object