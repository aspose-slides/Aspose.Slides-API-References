---
title: MathMatrix
second_title: Aspose.Slides for Android qua Tham chiếu API Java
description: Xác định đối tượng Matrix bao gồm các phần tử con được sắp xếp thành một hoặc nhiều hàng và cột.
type: docs
url: /vi/com.aspose.slides/mathmatrix/
---
**Kế thừa:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện đã thực thi:**  
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Xác định đối tượng Matrix, bao gồm các phần tử con được sắp xếp thành một hoặc nhiều hàng và cột. Cần lưu ý rằng ma trận không có dấu phân cách tích hợp. Để đặt ma trận trong dấu ngoặc, bạn nên sử dụng đối tượng dấu phân cách (IMathDelimiter). Các đối số null có thể được dùng để tạo khoảng trống trong ma trận.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Khởi tạo một thể hiện mới của lớp MathMatrix. |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRowCount()](#getRowCount--) | Số hàng trong ma trận |
| [getColumnCount()](#getColumnCount--) | Số cột trong ma trận |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ẩn các trình giữ chỗ cho các phần tử ma trận trống Mặc định: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ẩn các trình giữ chỗ cho các phần tử ma trận trống Mặc định: false |
| [getBaseJustification()](#getBaseJustification--) | Xác định căn chỉnh dọc so với văn bản xung quanh. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Xác định căn chỉnh dọc so với văn bản xung quanh. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Chiều rộng cột tối thiểu tính bằng twip (1/20 điểm). Khoảng cách giữa các cột (cũng được gọi là \u201cColumn Gap\u201d hoặc \u201cGap Width\u201d) được cộng vào MinColumnWidth để xác định Tổng Khoảng Cách Cột Ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Chiều rộng cột tối thiểu tính bằng twip (1/20 điểm). Khoảng cách giữa các cột (cũng được gọi là \u201cColumn Gap\u201d hoặc \u201cGap Width\u201d) được cộng vào MinColumnWidth để xác định Tổng Khoảng Cách Cột Ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). |
| [getColumnGapRule()](#getColumnGapRule--) | Kiểu khoảng cách ngang giữa các cột của ma trận; đơn vị khoảng cách ngang có thể là ems hoặc points (được lưu dưới dạng twip). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Kiểu khoảng cách ngang giữa các cột của ma trận; đơn vị khoảng cách ngang có thể là ems hoặc points (được lưu dưới dạng twip). |
| [getColumnGap()](#getColumnGap--) | Giá trị của khoảng cách ngang giữa các cột của ma trận; nếu ColumnGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twip (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là số bội của 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Giá trị của khoảng cách ngang giữa các cột của ma trận; nếu ColumnGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twip (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là số bội của 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Kiểu khoảng cách dọc giữa các hàng của ma trận; đơn vị khoảng cách dọc có thể là lines hoặc points (được lưu dưới dạng twip). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Kiểu khoảng cách dọc giữa các hàng của ma trận; đơn vị khoảng cách dọc có thể là lines hoặc points (được lưu dưới dạng twip). |
| [getRowGap()](#getRowGap--) | Giá trị của khoảng cách dọc giữa các hàng của ma trận; nếu RowGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twip (1/20 điểm). Nếu RowGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là nửa dòng. |
| [setRowGap(long value)](#setRowGap-long-) | Giá trị của khoảng cách dọc giữa các hàng của ma trận; nếu RowGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twip (1/20 điểm). Nếu RowGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là nửa dòng. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Phần tử của ma trận |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Phần tử của ma trận |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Lấy căn chỉnh ngang của cột được chỉ định |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Đặt căn chỉnh ngang của cột được chỉ định |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Đặt căn chỉnh ngang của các cột được chỉ định |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Chèn một hàng mới trước hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Chèn một hàng mới sau hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Xóa hàng được chỉ định |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Chèn một cột mới trước cột được chỉ định. Ban đầu tất cả các phần tử trong cột mới đều là null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Chèn một cột mới sau cột được chỉ định. Ban đầu tất cả các phần tử trong cột mới đều là null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Xóa cột được chỉ định |
| [getChildren()](#getChildren--) | Lấy các phần tử con |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Khởi tạo một thể hiện mới của lớp MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| rowCount | int | số lượng hàng |
| columnCount | int | số lượng cột |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Số hàng trong ma trận

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Trả về:**  
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Số cột trong ma trận

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Trả về:**  
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Ẩn các trình giữ chỗ cho các phần tử ma trận trống Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Trả về:**  
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Ẩn các trình giữ chỗ cho các phần tử ma trận trống Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Xác định căn chỉnh dọc so với văn bản xung quanh. Các giá trị có thể là top, bottom và center. Mặc định: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Trả về:**  
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Xác định căn chỉnh dọc so với văn bản xung quanh. Các giá trị có thể là top, bottom và center. Mặc định: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Chiều rộng cột tối thiểu tính bằng twip (1/20 điểm). Khoảng cách giữa các cột (cũng được gọi là \u201cColumn Gap\u201d hoặc \u201cGap Width\u201d) được cộng vào MinColumnWidth để xác định Tổng Khoảng Cách Cột Ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). Mặc định: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Trả về:**  
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Chiều rộng cột tối thiểu tính bằng twip (1/20 điểm). Khoảng cách giữa các cột (cũng được gọi là \u201cColumn Gap\u201d hoặc \u201cGap Width\u201d) được cộng vào MinColumnWidth để xác định Tổng Khoảng Cách Cột Ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). Mặc định: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

Kiểu khoảng cách ngang giữa các cột của ma trận; đơn vị khoảng cách ngang có thể là ems hoặc points (được lưu dưới dạng twip). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Trả về:**  
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Kiểu khoảng cách ngang giữa các cột của ma trận; đơn vị khoảng cách ngang có thể là ems hoặc points (được lưu dưới dạng twip). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

Giá trị của khoảng cách ngang giữa các cột của ma trận; nếu ColumnGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twip (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là số bội của 0.5 em. Trong các trường hợp khác sẽ bị bỏ qua. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Trả về:**  
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

Giá trị của khoảng cách ngang giữa các cột của ma trận; nếu ColumnGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twip (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là số bội của 0.5 em. Trong các trường hợp khác sẽ bị bỏ qua. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

Kiểu khoảng cách dọc giữa các hàng của ma trận; đơn vị khoảng cách dọc có thể là lines hoặc points (được lưu dưới dạng twip). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Trả về:**  
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Kiểu khoảng cách dọc giữa các hàng của ma trận; đơn vị khoảng cách dọc có thể là lines hoặc points (được lưu dưới dạng twip). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

Giá trị của khoảng cách dọc giữa các hàng của ma trận; nếu RowGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twip (1/20 điểm). Nếu RowGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là nửa dòng. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Trả về:**  
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

Giá trị của khoảng cách dọc giữa các hàng của ma trận; nếu RowGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twip (1/20 điểm). Nếu RowGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là nửa dòng. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Phần tử của ma trận

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| row | int | Chỉ mục dựa trên 0 của hàng cần lấy phần tử |
| column | int | Chỉ mục dựa trên 0 của cột cần lấy phần tử |

**Trả về:**  
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Phần tử của ma trận

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| row | int | Chỉ mục dựa trên 0 của hàng cần lấy phần tử |
| column | int | Chỉ mục dựa trên 0 của cột cần lấy phần tử |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Thuộc tính ký tự điều khiển

**Trả về:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Lấy căn chỉnh ngang của cột được chỉ định

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục cột dựa trên 0 |

**Trả về:**  
int - Căn chỉnh ngang của cột được chỉ định
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Đặt căn chỉnh ngang của cột được chỉ định

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục cột dựa trên 0 |
| val | int | Giá trị mới của căn chỉnh ngang cho cột được chỉ định |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Đặt căn chỉnh ngang của các cột được chỉ định

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục dựa trên 0 của cột đầu tiên cần đặt căn chỉnh |
| columnsCount | long | Số lượng cột cần xác định căn chỉnh |
| val | int | Giá trị mới của căn chỉnh ngang cho cột được chỉ định |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Chèn một hàng mới trước hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| rowIndex | int | Chỉ số của hàng trước đó sẽ chèn hàng mới |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Chèn một hàng mới sau hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| rowIndex | int | Chỉ số của hàng sau đó sẽ chèn hàng mới |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Xóa hàng được chỉ định

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| rowIndex | int | Chỉ mục dựa trên 0 của hàng cần xóa. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Chèn một cột mới trước cột được chỉ định. Ban đầu tất cả các phần tử trong cột mới đều là null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ số của cột trước đó sẽ chèn cột mới |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Chèn một cột mới sau cột được chỉ định. Ban đầu tất cả các phần tử trong cột mới đều là null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ số của cột sau đó sẽ chèn cột mới |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Xóa cột được chỉ định

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục dựa trên 0 của cột cần xóa. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lấy các phần tử con

**Trả về:**  
com.aspose.slides.IMathElement[]