---
title: IChartSeriesCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho tập hợp của
type: docs
url: /vi/com.aspose.slides/ichartseriescollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Đại diện cho tập hợp của [IChartSeries](../../com.aspose.slides/ichartseries)
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Nhận phần tử tại chỉ mục đã chỉ định. |
| [add(int type)](#add-int-) | Tạo chuỗi biểu đồ mới và thêm vào tập hợp. |
| [insert(int index, int type)](#insert-int-int-) | Tạo chuỗi biểu đồ mới và chèn vào tập hợp. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Tạo chuỗi biểu đồ mới từ [IChartDataCell](../../com.aspose.slides/ichartdatacell) và thêm vào tập hợp. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Tạo chuỗi biểu đồ mới từ [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) và thêm vào tập hợp. |
| [add(String name, int type)](#add-java.lang.String-int-) | Tạo chuỗi biểu đồ mới từ giá trị và thêm vào tập hợp. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Tìm kiếm [IChartSeries](../../com.aspose.slides/ichartseries) đã chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Xóa giá trị đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định |
| [clear()](#clear--) | Xóa tất cả các phần tử (bao gồm kiểu biểu đồ) khỏi tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Nhận phần tử tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Phần tử tại chỉ mục đã chỉ định.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Tạo chuỗi biểu đồ mới và thêm vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kiểu của chuỗi |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Chuỗi biểu đồ mới.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Tạo chuỗi biểu đồ mới và chèn vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục để chèn |
| type | int | Kiểu biểu đồ [ChartType](../../com.aspose.slides/charttype) |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Chuỗi biểu đồ mới [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Tạo chuỗi biểu đồ mới từ [IChartDataCell](../../com.aspose.slides/ichartdatacell) và thêm vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ô chứa tên chuỗi. |
| type | int | Kiểu đặt cho chuỗi |

--------------------

Nếu chuỗi biểu đồ được tạo từ cùng một ô đã có trong tập hợp thì phương thức không thêm gì và trả về chỉ mục của nó.

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Chuỗi biểu đồ đã thêm hoặc chuỗi đã có trong tập hợp.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Tạo chuỗi biểu đồ mới từ [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) và thêm vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Các ô chứa tên chuỗi. |
| type | int | Kiểu đặt cho chuỗi |

--------------------

Nếu chuỗi biểu đồ được tạo từ cùng một ô đã có trong tập hợp thì phương thức không thêm gì và trả về chỉ mục của nó.

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Chuỗi biểu đồ đã thêm hoặc chuỗi đã có trong tập hợp.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Tạo chuỗi biểu đồ mới từ giá trị và thêm vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên chuỗi. |
| type | int | Kiểu đặt cho chuỗi |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Chuỗi biểu đồ đã thêm.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Tìm kiếm [IChartSeries](../../com.aspose.slides/ichartseries) đã chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Giá trị chuỗi biểu đồ. |

**Trả về:**
int - Chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của giá trị trong toàn bộ CollectionBase, nếu tìm thấy; nếu không, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Xóa giá trị đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Giá trị. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục int |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử (bao gồm kiểu biểu đồ) khỏi tập hợp.