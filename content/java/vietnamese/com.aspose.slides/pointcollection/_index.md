---
title: PointCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho tập hợp các điểm hoạt ảnh.
type: docs
url: /vi/com.aspose.slides/pointcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Đại diện cho tập hợp các điểm hoạt ảnh.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Trả về số lượng điểm trong tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về một điểm tại chỉ mục được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Trả về số lượng điểm trong tập hợp. Kiểu int chỉ đọc.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Trả về một điểm tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử. |

**Trả về:**
[IPoint](../../com.aspose.slides/ipoint) - Đối tượng [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Trả về một enumerator duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Một IGenericEnumerator có thể được sử dụng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Một java.util.Iterator cho toàn bộ tập hợp.