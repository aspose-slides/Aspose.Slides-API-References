---
title: IMathMatrix
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định đối tượng Matrix bao gồm các phần tử con được bố trí trong một hoặc nhiều hàng và cột.
type: docs
url: /vi/com.aspose.slides/imathmatrix/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Xác định đối tượng Matrix, bao gồm các phần tử con được sắp xếp trong một hoặc nhiều hàng và cột. Cần lưu ý rằng ma trận không có dấu phân cách tích hợp. Để đặt ma trận trong dấu ngoặc, bạn nên sử dụng đối tượng delimiter (IMathDelimiter). Các đối số null có thể được sử dụng để tạo khoảng trống trong ma trận.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Các phần tử của ma trận |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Các phần tử của ma trận |
| [getRowCount()](#getRowCount--) | Số hàng trong ma trận |
| [getColumnCount()](#getColumnCount--) | Số cột trong ma trận |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ẩn các placeholder cho các phần tử ma trận trống. Mặc định: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ẩn các placeholder cho các phần tử ma trận trống. Mặc định: false |
| [getBaseJustification()](#getBaseJustification--) | Xác định căn dọc so với văn bản xung quanh. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Xác định căn dọc so với văn bản xung quanh. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Chiều rộng cột tối thiểu tính bằng twips (1/20 điểm). Khoảng cách khe (cũng được gọi là \\u201cColumn Gap\\u201d hoặc \\u201cGap Width\\u201d) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột ma trận (khoảng cách giữa các cạnh tương đồng của các cột khác nhau). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Chiều rộng cột tối thiểu tính bằng twips (1/20 điểm). Khoảng cách khe (cũng được gọi là \\u201cColumn Gap\\u201d hoặc \\u201cGap Width\\u201d) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột ma trận (khoảng cách giữa các cạnh tương đồng của các cột khác nhau). |
| [getColumnGapRule()](#getColumnGapRule--) | Kiểu khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là em hoặc điểm (được lưu dưới dạng twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Kiểu khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là em hoặc điểm (được lưu dưới dạng twips). |
| [getColumnGap()](#getColumnGap--) | Giá trị khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là số lần tăng 0,5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Giá trị khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là số lần tăng 0,5 em. |
| [getRowGapRule()](#getRowGapRule--) | Kiểu khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là dòng hoặc điểm (được lưu dưới dạng twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Kiểu khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là dòng hoặc điểm (được lưu dưới dạng twips). |
| [getRowGap()](#getRowGap--) | Giá trị khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là nửa dòng. |
| [setRowGap(long value)](#setRowGap-long-) | Giá trị khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là nửa dòng. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Lấy căn chỉnh ngang của cột được chỉ định |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Đặt căn chỉnh ngang của cột được chỉ định |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Đặt căn chỉnh ngang của các cột được chỉ định |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Chèn một hàng mới trước hàng được chỉ định. Ban đầu, tất cả các phần tử trong hàng mới đều là null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Chèn một hàng mới sau hàng được chỉ định. Ban đầu, tất cả các phần tử trong hàng mới đều là null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Xóa hàng được chỉ định |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Chèn một cột mới trước cột được chỉ định. Ban đầu, tất cả các phần tử trong cột mới đều là null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Chèn một cột mới sau cột được chỉ định. Ban đầu, tất cả các phần tử trong cột mới đều là null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Xóa cột được chỉ định |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Các phần tử của ma trận

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
| row | int | Chỉ mục bắt đầu từ 0 của hàng để lấy mục |
| column | int | Chỉ mục bắt đầu từ 0 của cột để lấy mục |

**Giá trị trả về:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Các phần tử của ma trận

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
| row | int | Chỉ mục bắt đầu từ 0 của hàng để lấy mục |
| column | int | Chỉ mục bắt đầu từ 0 của cột để lấy mục |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Số hàng trong ma trận

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Giá trị trả về:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Số cột trong ma trận

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Giá trị trả về:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Ẩn các placeholder cho các phần tử ma trận trống. Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Giá trị trả về:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Ẩn các placeholder cho các phần tử ma trận trống. Mặc định: false

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
public abstract int getBaseJustification()
```

Xác định căn dọc so với văn bản xung quanh. Các giá trị có thể là top, bottom và center. Mặc định: Center

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Giá trị trả về:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Xác định căn dọc so với văn bản xung quanh. Các giá trị có thể là top, bottom và center. Mặc định: Center

--------------------

> ```
> Ví dụ:
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
public abstract long getMinColumnWidth()
```

Chiều rộng cột tối thiểu tính bằng twips (1/20 điểm). Khoảng cách khe (cũng được gọi là \\u201cColumn Gap\\u201d hoặc \\u201cGap Width\\u201d) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột ma trận (khoảng cách giữa các cạnh tương đồng của các cột khác nhau). Mặc định: 0.

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Giá trị trả về:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Chiều rộng cột tối thiểu tính bằng twips (1/20 điểm). Khoảng cách khe (cũng được gọi là \\u201cColumn Gap\\u201d hoặc \\u201cGap Width\\u201d) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột ma trận (khoảng cách giữa các cạnh tương đồng của các cột khác nhau). Mặc định: 0.

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
public abstract int getColumnGapRule()
```

Kiểu khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là em hoặc điểm (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Giá trị trả về:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

Kiểu khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là em hoặc điểm (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Ví dụ:
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
public abstract long getColumnGap()
```

Giá trị khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là số lần tăng 0,5 em. Trong các trường hợp khác bị bỏ qua. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Giá trị trả về:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

Giá trị khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là số lần tăng 0,5 em. Trong các trường hợp khác bị bỏ qua. Mặc định: 0

--------------------

> ```
> Ví dụ:
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
public abstract int getRowGapRule()
```

Kiểu khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là dòng hoặc điểm (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Giá trị trả về:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Kiểu khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là dòng hoặc điểm (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Ví dụ:
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
public abstract long getRowGap()
```

Giá trị khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là nửa dòng. Mặc định: 0

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Giá trị trả về:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

Giá trị khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 (“Exactly”), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 (“Multiple”), đơn vị được hiểu là nửa dòng. Mặc định: 0

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Lấy căn chỉnh ngang của cột được chỉ định

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục cột bắt đầu từ 0 |

**Giá trị trả về:**
int - Căn chỉnh ngang của cột được chỉ định

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Đặt căn chỉnh ngang của cột được chỉ định

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục cột bắt đầu từ 0 |
| val | int | Giá trị mới của căn chỉnh ngang của cột được chỉ định |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Đặt căn chỉnh ngang của các cột được chỉ định

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục bắt đầu từ 0 của cột đầu tiên để đặt căn chỉnh |
| columnsCount | long | Số cột cần chỉ định căn chỉnh |
| val | int | Giá trị mới của căn chỉnh ngang của cột được chỉ định |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Chèn một hàng mới trước hàng được chỉ định. Ban đầu, tất cả các phần tử trong hàng mới đều là null.

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| rowIndex | int | Chỉ mục của hàng trước đó sẽ chèn hàng mới |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Chèn một hàng mới sau hàng được chỉ định. Ban đầu, tất cả các phần tử trong hàng mới đều là null.

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| rowIndex | int | Chỉ mục của hàng sau đó sẽ chèn hàng mới |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Xóa hàng được chỉ định

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| rowIndex | int | Chỉ mục bắt đầu từ 0 của hàng cần xóa. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Chèn một cột mới trước cột được chỉ định. Ban đầu, tất cả các phần tử trong cột mới đều là null.

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục của cột trước đó sẽ chèn cột mới |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Chèn một cột mới sau cột được chỉ định. Ban đầu, tất cả các phần tử trong cột mới đều là null.

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục của cột sau đó sẽ chèn cột mới |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Xóa cột được chỉ định

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int | Chỉ mục bắt đầu từ 0 của cột cần xóa. |