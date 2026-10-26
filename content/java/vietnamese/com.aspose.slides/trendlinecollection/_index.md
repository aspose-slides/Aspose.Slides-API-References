---
title: TrendlineCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập của Trendline
type: docs
url: /vi/com.aspose.slides/trendlinecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Đại diện cho một bộ sưu tập của Trendline
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [add(int trendlineType)](#add-int-) | Thêm Trendline mới vào cuối một bộ sưu tập và trả về nó. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Xóa giá trị được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [getCount()](#getCount--) | Lấy số phần tử thực sự có trong bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định. Chỉ-đọc [Trendline](../../com.aspose.slides/trendline).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Thêm Trendline mới vào cuối một bộ sưu tập và trả về nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| trendlineType | int |  |

**Trả về:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Xóa giá trị được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### getCount() {#getCount--}
```
public final int getCount()
```

Lấy số phần tử thực sự có trong bộ sưu tập. Chỉ-đọc int.

**Trả về:**
int