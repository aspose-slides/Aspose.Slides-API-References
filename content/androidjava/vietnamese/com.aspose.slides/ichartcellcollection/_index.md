---
title: IChartCellCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn tập hợp các ô có dữ liệu.
type: docs
url: /vi/com.aspose.slides/ichartcellcollection/
---
**Tất cả các giao diện được thực hiện:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Biểu diễn tập hợp các ô có dữ liệu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Trả về địa chỉ của tập hợp các ô trong workbook. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Chuỗi kết hợp từ tất cả các giá trị chuỗi của ô. |
| [get_Item(int index)](#get-Item-int-) | Trả về một ô (IChartDataCell) theo chỉ số. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Thêm ô mới vào tập hợp. |
| [add(Object value)](#add-java.lang.Object-) | Tạo [IChartDataCell](../../com.aspose.slides/ichartdatacell) từ giá trị được chỉ định và thêm vào tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa một ô khỏi tập hợp theo chỉ số. |
| [getCount()](#getCount--) | Lấy số lượng ô trong tập hợp. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

Trả về địa chỉ của tập hợp các ô trong workbook.

**Trả về:**
java.lang.String - Địa chỉ của tập hợp các ô trong workbook String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

Chuỗi kết hợp từ tất cả các giá trị chuỗi của ô.

**Trả về:**
java.lang.String - Chuỗi kết quả String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

Trả về một ô (IChartDataCell) theo chỉ số.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của một ô. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Ô có dữ liệu.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

Thêm ô mới vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ô mới để thêm. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

Tạo [IChartDataCell](../../com.aspose.slides/ichartdatacell) từ giá trị được chỉ định và thêm vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object | Giá trị.

--------------------

Phương thức này thêm worksheet có tên AUTO_DATA và thêm tất cả các giá trị vào đó. Nếu bạn sử dụng [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) để thêm hoặc chỉnh sửa giá trị Cell, hãy chắc chắn rằng bạn không sử dụng worksheet này. Số lượng giá trị tối đa có thể thêm bằng phương thức này không được vượt quá 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa một ô khỏi tập hợp theo chỉ số.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của ô cần xóa. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số lượng ô trong tập hợp. Chỉ đọc int.

**Trả về:**
int