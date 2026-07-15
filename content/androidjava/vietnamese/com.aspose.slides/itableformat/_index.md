---
title: ITableFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho định dạng của một bảng.
type: docs
url: /vi/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Đại diện cho định dạng của một bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Trả về một đối tượng thuộc tính tô màu bảng. |
| [getTransparency()](#getTransparency--) | Lấy hoặc đặt độ trong suốt của màu tô. |
| [setTransparency(float value)](#setTransparency-float-) | Lấy hoặc đặt độ trong suốt của màu tô. |
| [getEffective()](#getEffective--) | Lấy các thuộc tính định dạng bảng hiệu quả với kế thừa và áp dụng kiểu bảng. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Trả về một đối tượng thuộc tính tô màu bảng. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Lấy hoặc đặt độ trong suốt của màu tô. Đọc/ghi float .

**Trả về:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Lấy hoặc đặt độ trong suốt của màu tô. Đọc/ghi float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Lấy các thuộc tính định dạng bảng hiệu quả với kế thừa và áp dụng kiểu bảng.

**Trả về:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).