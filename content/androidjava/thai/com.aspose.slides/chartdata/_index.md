---
title: ChartData
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงข้อมูลที่ใช้สำหรับการวาดแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartdata/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)  
```
public class ChartData extends DomObject<Chart> implements IChartData
```

แสดงข้อมูลที่ใช้สำหรับการพล็อตแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | รับ factory ของเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ. |
| [getSeries()](#getSeries--) | รับซีรีส์. |
| [getSeriesGroups()](#getSeriesGroups--) | รับกลุ่มของซีรีส์. |
| [getCategories()](#getCategories--) | รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและหมวดหมู่รองถ้า property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | ถ้าเป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | ถ้าเป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. |
| [getSecondaryCategories()](#getSecondaryCategories--) | รับหมวดหมู่รองถ้า property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น true. |
| [readWorkbookStream()](#readWorkbookStream--) | เขียนไฟล์ Excel workbook ที่บรรจุภายในลงในสตรีมในหน่วยความจำ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | เริ่มต้นไฟล์ Excel workbook ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ. |
| [getDataSourceType()](#getDataSourceType--) | แสดงเส้นทางของ workbook ภายนอกถ้าเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | แสดงแหล่งข้อมูลของแผนภูมิ. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | รับประเภทของ workbook ที่ฝังอยู่. |
| [getRange()](#getRange--) | รับช่วงข้อมูลของแผนภูมิ. |
| [setRange(String formula)](#setRange-java.lang.String-) | ตั้งค่าช่วงข้อมูลของแผนภูมิ. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [switchRowColumn()](#switchRowColumn--) | สลับข้อมูลข้ามแกน. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

รับ factory ของเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ. อ่านอย่างเดียว [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**คืนค่า:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

รับซีรีส์. อ่านอย่างเดียว [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**คืนค่า:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

รับกลุ่มของซีรีส์. อ่านอย่างเดียว [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) แต่ละกลุ่มของซีรีส์จะมีซีรีส์ที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของซีรีส์จะมีซีรีส์ที่ถูกแผนภูมิคณิตบนแกนหลักหรือแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียว). ดังนั้นหลักการของการจัดกลุ่มซีรีส์คือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการพลอตบนแกนหลัก/รอง. 2) กลุ่มของซีรีส์จะมีคุณสมบัติของซีรีส์บางอย่างที่เป็นค่าร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม (“series group properties”). “Series group properties” ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน. แต่ละ “series group properties” สามารถมีการฉายภาพอ่านอย่างเดียวในคลาส ChartSeries.

**คืนค่า:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและหมวดหมู่รองถ้า property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false). อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // หมวดหมู่ที่เกี่ยวข้องคือ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // หมวดหมู่ที่เกี่ยวข้องคือ series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

ถ้า property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. ถ้า property ดังกล่าวเป็น true แล้วข้อมูลใน property \#getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลใน property \#getCategories.getCategories จะใช้สำหรับซีรีส์หลัก.

**คืนค่า:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

ถ้าเป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. ถ้าเป็น true แล้วข้อมูลใน property \#getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลใน property \#getCategories.getCategories จะใช้สำหรับซีรีส์หลัก. อ่าน/เขียน boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // หมวดหมู่ที่เกี่ยวข้องคือ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // หมวดหมู่ที่เกี่ยวข้องคือ series.getChart().getChartData().getCategories()
>  }
> ```

**คืนค่า:**  
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

ถ้าเป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. ถ้าเป็น true แล้วข้อมูลใน property \#getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลใน property \#getCategories.getCategories จะใช้สำหรับซีรีส์หลัก. อ่าน/เขียน boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // หมวดหมู่ที่เกี่ยวข้องคือ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // หมวดหมู่ที่เกี่ยวข้องคือ series.getChart().getChartData().getCategories()
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

รับหมวดหมู่รองถ้า property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น true. อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // หมวดหมู่ที่เกี่ยวข้องคือ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // หมวดหมู่ที่เกี่ยวข้องคือ series.getChart().getChartData().getCategories()
>  }
> ```

ถ้า property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. ถ้า property ดังกล่าวเป็น true แล้วข้อมูลใน property \#getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลใน property \#getCategories.getCategories จะใช้สำหรับซีรีส์หลัก.

**คืนค่า:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

เขียนไฟล์ Excel workbook ที่บรรจุภายในลงในสตรีมในหน่วยความจำ.

**คืนค่า:**  
byte[] - คืนค่าอาเรย์ของไบต์ที่มีสำเนาของ Excel workbook ที่บรรจุภายใน.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

เริ่มต้นไฟล์ Excel workbook ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ms | byte[] | สตรีมที่ผู้ใช้ระบุที่มี Excel workbook ทั้งหมด. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

แสดงเส้นทางของ workbook ภายนอกถ้าเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น null.

**คืนค่า:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

แสดงแหล่งข้อมูลของแผนภูมิ.

**คืนค่า:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

รับประเภทของ workbook ที่ฝังอยู่. คืนค่า [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) ถ้า DataSourceType (\#getDataSourceType.getDataSourceType) เป็น [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). อ่านอย่างเดียว [WorkbookType](../../com.aspose.slides/workbooktype).

**คืนค่า:**  
int

### getRange() {#getRange--}
```
public final String getRange()
```

รับช่วงข้อมูลของแผนภูมิ.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**คืนค่า:**  
java.lang.String - สูตรช่วงข้อมูลของเซลล์. เช่น: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

ตั้งค่าช่วงข้อมูลของแผนภูมิ. ซีรีส์และหมวดหมู่จะอัปเดตตามช่วงข้อมูลใหม่. ถ้าจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในข้อมูลแผนภูมิ จะมีการเพิ่มซีรีส์ใหม่ที่มีประเภทเดียวกับซีรีส์สุดท้ายในคอลเลกชันปัจจุบันไปยังท้ายคอลเลกชัน.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตรช่วงข้อมูลของเซลล์. เช่น: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะอัปเดตจาก workbook เป้าหมาย.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| workbookPath | java.lang.String | เส้นทางไปยัง workbook เป้าหมาย |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| workbookPath | java.lang.String | เส้นทางไปยัง workbook เป้าหมาย |
| updateChartData | boolean | ถ้าค่าเป็น false จะอัปเดตเฉพาะเส้นทางของ workbook เท่านั้น. ข้อมูลแผนภูมิจะไม่ถูกโหลดและอัปเดตจาก workbook เป้าหมาย. ใช้ได้เมื่อ workbook เป้าหมายไม่มีหรือไม่พร้อมใช้งาน. ถ้าค่าเป็น true ข้อมูลแผนภูมิจะอัปเดตจาก workbook เป้าหมาย. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

สลับข้อมูลข้ามแกน. ข้อมูลที่แสดงบนแกน X จะย้ายไปยังแกน Y และกลับกัน.