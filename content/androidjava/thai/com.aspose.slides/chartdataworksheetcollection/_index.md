---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: แสดงถึงคอลเลกชันของแผ่นงานในสมุดข้อมูลแผนภูมิ
type: docs
url: /th/com.aspose.slides/chartdataworksheetcollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

แสดงถึงคอลเลกชันของแผ่นงานของสมุดข้อมูลแผนภูมิ

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

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าแผ่นงานตามดัชนี. |
| [size()](#size--) | คืนค่าจำนวน. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากฐานการซิงโครไนซ์. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```


คืนค่าแผ่นงานตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแผ่นงานในคอลเลกชัน. |

**คืนค่า:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - ตัวอย่างของ IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```


คืนค่าจำนวน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```


คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```


คัดลอกไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์ที่ต้องการคัดลอกไป. |
| arrayIndex | int | ดัชนีเริ่มคัดลอก. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่ารากฐานการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object