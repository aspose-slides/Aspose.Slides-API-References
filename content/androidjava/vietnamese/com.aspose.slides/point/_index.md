---
title: Point
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Biểu diễn điểm hoạt ảnh.
type: docs
url: /vi/com.aspose.slides/point/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Biểu diễn điểm hoạt ảnh.
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [Point()](#Point--) | Hàm tạo mặc định. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Tạo điểm hoạt ảnh với thời gian, giá trị và công thức. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTime()](#getTime--) | Biểu diễn giá trị thời gian. |
| [setTime(float value)](#setTime-float-) | Biểu diễn giá trị thời gian. |
| [getValue()](#getValue--) | Biểu diễn giá trị điểm. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Biểu diễn giá trị điểm. |
| [getFormula()](#getFormula--) | Công thức trong các thuộc tính values, from, to, by có thể được tạo thành từ những thành phần sau: Toán tử số học chuẩn: '+', '-', '*', '/', '^', '%' (mod) Hằng số: 'pi' 'e' Toán tử điều kiện: 'abs', 'min', 'max', '?' (if) Toán tử so sánh: '==', '>=', '', '!=', '!' Toán tử lượng giác: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarit tự nhiên 'ln()' Tham chiếu thuộc tính (các thuộc tính được host hỗ trợ) ví dụ: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Đọc/ghi String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Công thức trong các thuộc tính values, from, to, by có thể được tạo thành từ những thành phần sau: Toán tử số học chuẩn: '+', '-', '*', '/', '^', '%' (mod) Hằng số: 'pi' 'e' Toán tử điều kiện: 'abs', 'min', 'max', '?' (if) Toán tử so sánh: '==', '>=', '', '!=', '!' Toán tử lượng giác: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarit tự nhiên 'ln()' Tham chiếu thuộc tính (các thuộc tính được host hỗ trợ) ví dụ: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Đọc/ghi String. |
### Point() {#Point--}
```
public Point()
```

Hàm tạo mặc định.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Tạo điểm hoạt ảnh với thời gian, giá trị và công thức.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| time | float | Giá trị thời gian. |
| value | java.lang.Object | Giá trị điểm. |
| formula | java.lang.String | Công thức. |

### getTime() {#getTime--}
```
public final float getTime()
```

Biểu diễn giá trị thời gian. Đọc/ghi float.

**Trả về:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Biểu diễn giá trị thời gian. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Biểu diễn giá trị điểm. Chỉ: bool, ColorFormat, float, int, string. Đọc/ghi Object.

**Trả về:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Biểu diễn giá trị điểm. Chỉ: bool, ColorFormat, float, int, string. Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Công thức trong các thuộc tính values, from, to, by có thể được tạo thành từ những thành phần sau: Toán tử số học chuẩn: '+', '-', '*', '/', '^', '%' (mod) Hằng số: 'pi' 'e' Toán tử điều kiện: 'abs', 'min', 'max', '?' (if) Toán tử so sánh: '==', '>=', '', '!=', '!' Toán tử lượng giác: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarit tự nhiên 'ln()' Tham chiếu thuộc tính (các thuộc tính được host hỗ trợ) ví dụ: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Đọc/ghi String.

**Trả về:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Công thức trong các thuộc tính values, from, to, by có thể được tạo thành từ những thành phần sau: Toán tử số học chuẩn: '+', '-', '*', '/', '^', '%' (mod) Hằng số: 'pi' 'e' Toán tử điều kiện: 'abs', 'min', 'max', '?' (if) Toán tử so sánh: '==', '>=', '', '!=', '!' Toán tử lượng giác: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarit tự nhiên 'ln()' Tham chiếu thuộc tính (các thuộc tính được host hỗ trợ) ví dụ: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |