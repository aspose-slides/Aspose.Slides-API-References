---
title: ITrendlineCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị một tập hợp của TrendlineEx
type: docs
url: /vi/com.aspose.slides/itrendlinecollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Biểu thị một tập hợp của TrendlineEx
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [getCount()](#getCount--) | Lấy số lượng phần tử thực sự chứa trong tập hợp. |
| [add(int trendlineType)](#add-int-) | Thêm Trendline mới vào cuối tập hợp và trả về nó. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Xóa giá trị được chỉ định. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [ITrendline](../../com.aspose.slides/itrendline).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Lấy số lượng phần tử thực sự chứa trong tập hợp. Chỉ đọc int.

**Trả về:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Thêm Trendline mới vào cuối tập hợp và trả về nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| trendlineType | int | Loại Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Trả về:**
[ITrendline](../../com.aspose.slides/itrendline) - Trendline mới [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Xóa giá trị được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline để xóa [ITrendline](../../com.aspose.slides/itrendline) |