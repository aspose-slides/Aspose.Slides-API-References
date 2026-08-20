---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงคอลเลกชันของเวิร์กชีตในสมุดงานข้อมูลแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartdataworksheetcollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

แสดงถึงคอลเลกชันของเวิร์กชีตในสมุดงานข้อมูลแผนภูมิ.

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
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าเวิร์กชีตตามดัชนี. |
| [size()](#size--) | คืนค่าจำนวน. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันนั้นเป็นแบบซิงโครไนส์ (ปลอดภัยต่อเธรด) หรือไม่. |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากฐานการซิงโครไนส์. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

คืนค่าเวิร์กชีตตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเวิร์กชีตในคอลเลกชัน. |

**ผลลัพธ์:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - อินสแตนซ์ของ IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```

คืนค่าจำนวน. ค่าคงที่แบบอ่านอย่างเดียว int.

**ผลลัพธ์:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. ค่าคงที่แบบอ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

คัดลอกไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์ที่คัดลอกไป. |
| arrayIndex | int | ดัชนีที่เริ่มคัดลอก. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันนั้นเป็นแบบซิงโครไนส์ (ปลอดภัยต่อเธรด) หรือไม่. ค่าคงที่แบบอ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากฐานการซิงโครไนส์. ค่าคงที่แบบอ่านอย่างเดียว Object.

**ผลลัพธ์:**
java.lang.Object