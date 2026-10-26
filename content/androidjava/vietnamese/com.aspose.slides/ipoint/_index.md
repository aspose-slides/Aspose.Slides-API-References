---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn điểm hoạt ảnh.
type: docs
url: /vi/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Biểu diễn điểm hoạt ảnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTime()](#getTime--) | Biểu diễn giá trị thời gian. |
| [setTime(float value)](#setTime-float-) | Biểu diễn giá trị thời gian. |
| [getValue()](#getValue--) | Biểu diễn giá trị điểm. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Biểu diễn giá trị điểm. |
| [getFormula()](#getFormula--) | Toán tử số học chuẩn: '+', '-', '*', '/', '^', '%' (mod) Hằng số: 'pi' 'e' Toán tử điều kiện: 'abs', 'min', 'max', '?' (if) Toán tử so sánh: '==', '>=', '', '!=', '!' Toán tử lượng giác: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarit tự nhiên 'ln()' Tham chiếu thuộc tính (host supported properties) ví dụ: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Đọc/ghi String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Toán tử số học chuẩn: '+', '-', '*', '/', '^', '%' (mod) Hằng số: 'pi' 'e' Toán tử điều kiện: 'abs', 'min', 'max', '?' (if) Toán tử so sánh: '==', '>=', '', '!=', '!' Toán tử lượng giác: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarit tự nhiên 'ln()' Tham chiếu thuộc tính (host supported properties) ví dụ: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Đọc/ghi String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Biểu diễn giá trị thời gian. Đọc/ghi float.

**Trả về:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Biểu diễn giá trị thời gian. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Biểu diễn giá trị điểm. Only: bool, ColorFormat, float, int, string. Đọc/ghi Object.

**Trả về:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Biểu diễn giá trị điểm. Only: bool, ColorFormat, float, int, string. Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Toán tử số học chuẩn: '+', '-', '*', '/', '^', '%' (mod) Hằng số: 'pi' 'e' Toán tử điều kiện: 'abs', 'min', 'max', '?' (if) Toán tử so sánh: '==', '>=', '', '!=', '!' Toán tử lượng giác: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarit tự nhiên 'ln()' Tham chiếu thuộc tính (host supported properties) ví dụ: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Đọc/ghi String.

**Trả về:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Toán tử số học chuẩn: '+', '-', '*', '/', '^', '%' (mod) Hằng số: 'pi' 'e' Toán tử điều kiện: 'abs', 'min', 'max', '?' (if) Toán tử so sánh: '==', '>=', '', '!=', '!' Toán tử lượng giác: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarit tự nhiên 'ln()' Tham chiếu thuộc tính (host supported properties) ví dụ: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |