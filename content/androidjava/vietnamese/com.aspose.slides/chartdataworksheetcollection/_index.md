---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho tập hợp các worksheet của workbook dữ liệu biểu đồ.
type: docs
url: /vi/com.aspose.slides/chartdataworksheetcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Đại diện cho tập hợp các worksheet của workbook dữ liệu biểu đồ.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Phương thức

| Method | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về worksheet theo chỉ mục. |
| [size()](#size--) | Trả về số lượng. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết liệu việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

Trả về worksheet theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của worksheet trong bộ sưu tập. |

**Trả về:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Thực thể của IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```

Trả về số lượng. Read-only int.

**Trả về:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Read-only IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator that can be used to iterate through the collection.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator that can be used to iterate through the collection.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Sao chép vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng để sao chép vào. |
| arrayIndex | int | Chỉ mục để bắt đầu sao chép. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về một giá trị cho biết liệu việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. Read-only boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Read-only Object.

**Trả về:**
java.lang.Object