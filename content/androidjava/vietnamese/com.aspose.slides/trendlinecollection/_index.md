---
title: TrendlineCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một bộ sưu tập Trendline
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

Biểu diễn một bộ sưu tập Trendline
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(int trendlineType)](#add-int-) | Adds the new Trendline at the end of a collection and return it. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Removes the specified value. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Lấy phần tử tại chỉ số đã chỉ định. Chỉ đọc [Trendline](../../com.aspose.slides/trendline).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Thêm Trendline mới vào cuối bộ sưu tập và trả về nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| trendlineType | int |  |

**Giá trị trả về:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Xóa giá trị đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Trả về một enumerator cho phép duyệt qua bộ sưu tập.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### getCount() {#getCount--}
```
public final int getCount()
```

Lấy số phần tử thực sự có trong bộ sưu tập. Chỉ đọc int.

**Giá trị trả về:**
int