---
title: MathMatrix
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định đối tượng Matrix bao gồm các phần tử con được sắp xếp trong một hoặc nhiều hàng và cột.
type: docs
url: /vi/com.aspose.slides/mathmatrix/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Xác định đối tượng Matrix, bao gồm các phần tử con được sắp xếp trong một hoặc nhiều hàng và cột. Điều quan trọng cần lưu ý là ma trận không có dấu phân cách tích hợp. Để đặt ma trận trong dấu ngoặc, bạn nên sử dụng đối tượng dấu phân cách (IMathDelimiter). Các đối số null có thể được sử dụng để tạo khoảng trống trong ma trận.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Hàm tạo

| Constructor | Description |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Khởi tạo một thể hiện mới của lớp MathMatrix. |
## Phương thức

| Method | Description |
| --- | --- |
| [getRowCount()](#getRowCount--) | Số hàng trong ma trận |
| [getColumnCount()](#getColumnCount--) | Số cột trong ma trận |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ẩn các placeholder cho các phần tử ma trận trống. Mặc định: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ẩn các placeholder cho các phần tử ma trận trống. Mặc định: false |
| [getBaseJustification()](#getBaseJustification--) | Xác định căn dọc so với văn bản xung quanh. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Xác định căn dọc so với văn bản xung quanh. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Chiều rộng cột tối thiểu bằng twips (1/20 điểm). Khoảng cách khe (cũng được gọi là \\u201cColumn Gap\\u201d hoặc \\u201cGap Width\\u201d) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột của ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Chiều rộng cột tối thiểu bằng twips (1/20 điểm). Khoảng cách khe (cũng được gọi là \\u201cColumn Gap\\u201d hoặc \\u201cGap Width\\u201d) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột của ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). |
| [getColumnGapRule()](#getColumnGapRule--) | Kiểu khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là em hoặc point (được lưu dưới dạng twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Kiểu khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là em hoặc point (được lưu dưới dạng twips). |
| [getColumnGap()](#getColumnGap--) | Giá trị của khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 (\"Exactly\"), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (\"Multiple\"), đơn vị được hiểu là số lần tăng 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Giá trị của khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 (\"Exactly\"), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (\"Multiple\"), đơn vị được hiểu là số lần tăng 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Kiểu khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là dòng hoặc point (được lưu dưới dạng twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Kiểu khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là dòng hoặc point (được lưu dưới dạng twips). |
| [getRowGap()](#getRowGap--) | Giá trị của khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 (\"Exactly\"), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 (\"Multiple\"), đơn vị được hiểu là nửa dòng. |
| [setRowGap(long value)](#setRowGap-long-) | Giá trị của khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 (\"Exactly\"), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 (\"Multiple\"), đơn vị được hiểu là nửa dòng. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Phần tử của ma trận |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Phần tử của ma trận |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Lấy căn ngang của cột được chỉ định |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Đặt căn ngang của cột được chỉ định |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Đặt căn ngang của các cột được chỉ định |
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
| Parameter | Type | Description |
| --- | --- | --- |
| rowCount | int | số hàng |
| columnCount | int | số cột |

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

Ẩn các placeholder cho các phần tử ma trận trống. Mặc định: false

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

Ẩn các placeholder cho các phần tử ma trận trống. Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Xác định căn dọc so với văn bản xung quanh. Các giá trị có thể là top, bottom và center. Mặc định: Center

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

Xác định căn dọc so với văn bản xung quanh. Các giá trị có thể là top, bottom và center. Mặc định: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Chiều rộng cột tối thiểu bằng twips (1/20 điểm). Khoảng cách khe (cũng được gọi là \\u201cColumn Gap\\u201d hoặc \\u201cGap Width\\u201d) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột của ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). Mặc định: 0.

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

Chiều rộng cột tối thiểu bằng twips (1/20 điểm). Khoảng cách khe (cũng được gọi là \\u201cColumn Gap\\u201d hoặc \\u201cGap Width\\u201d) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột của ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). Mặc định: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

Kiểu khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là em hoặc point (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0)

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

Kiểu khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là em hoặc point (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

Giá trị của khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 (\"Exactly\"), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (\"Multiple\"), đơn vị được hiểu là số lần tăng 0.5 em. Trong các trường hợp khác sẽ bị bỏ qua. Mặc định: 0

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

Giá trị của khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 (\"Exactly\"), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 (\"Multiple\"), đơn vị được hiểu là số lần tăng 0.5 em. Trong các trường hợp khác sẽ bị bỏ qua. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

Kiểu khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là dòng hoặc point (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Ví dụ:
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

Kiểu khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là dòng hoặc point (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

Giá trị của khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 (\"Exactly\"), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 (\"Multiple\"), đơn vị được hiểu là nửa dòng. Mặc định: 0

--------------------

> ```
> Ví dụ:
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

Giá trị của khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 (\"Exactly\"), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 (\"Multiple\"), đơn vị được hiểu là nửa dòng. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Tham số:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | Chỉ số dựa trên zero của hàng cần lấy phần tử |
| column | int | Chỉ số dựa trên zero của cột cần lấy phần tử |
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
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | Chỉ số dựa trên zero của hàng cần lấy phần tử |
| column | int | Chỉ số dựa trên zero của cột cần lấy phần tử |
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

Lấy căn ngang của cột được chỉ định

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Chỉ số cột dựa trên zero |
**Trả về:**
int - Căn ngang của cột được chỉ định
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Đặt căn ngang của cột được chỉ định

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Chỉ số cột dựa trên zero |
| val | int | Giá trị mới của căn ngang của cột được chỉ định |
### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Đặt căn ngang của các cột được chỉ định

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Chỉ số dựa trên zero của cột đầu tiên cần đặt căn |
| columnsCount | long | Số cột cần xác định căn |
| val | int | Giá trị mới của căn ngang của cột được chỉ định |
### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Chèn một hàng mới trước hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null.

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Chỉ số hàng trước đó sẽ chèn hàng mới |
### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Chèn một hàng mới sau hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null.

--------------------

> ```
> Ví dụ:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Chỉ số hàng sau đó sẽ chèn hàng mới |
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
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Chỉ số dựa trên zero của hàng cần xóa. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Chỉ số cột trước đó sẽ chèn cột mới |
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
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Chỉ số cột sau đó sẽ chèn cột mới |
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
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Chỉ số dựa trên zero của cột cần xóa. |
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]