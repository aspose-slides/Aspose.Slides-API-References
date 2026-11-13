---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: แสดงข้อมูลที่ใช้สำหรับการวาดแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

แสดงข้อมูลที่ใช้สำหรับการวาดแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่. |
| [getSeries()](#getSeries--) | รับชุดข้อมูล. |
| [getSeriesGroups()](#getSeriesGroups--) | รับกลุ่มของชุดข้อมูล. |
| [getCategories()](#getCategories--) | รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรอง ถ้า property (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | หากเป็น false แล้ว property (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลใน property (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | หากเป็น false แล้ว property (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลใน property (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. |
| [getSecondaryCategories()](#getSecondaryCategories--) | รับหมวดหมู่รองถ้า property (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น true. |
| [readWorkbookStream()](#readWorkbookStream--) | เขียนเวิร์กบุ๊ก Excel ที่บรรจุอยู่ภายในลงในสตรีมในหน่วยความจำ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | ตั้งค่าเริ่มต้นเวิร์กบุ๊ก Excel ที่บรรจุอยู่ภายในโดยใช้ค่าที่ผู้ใช้ระบุ. |
| [setRange(String formula)](#setRange-java.lang.String-) | กำหนดช่วงข้อมูลแผนภูมิ. |
| [getRange()](#getRange--) | รับช่วงข้อมูลแผนภูมิ. |
| [getDataSourceType()](#getDataSourceType--) | แสดงแหล่งข้อมูลของแผนภูมิ |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | แสดงพาธของเวิร์กบุ๊กภายนอกหากแหล่งข้อมูลเป็นภายนอก, มิฉะนั้นเป็น null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | รับประเภทของเวิร์กบุ๊กที่ฝังอยู่. |
| [switchRowColumn()](#switchRowColumn--) | สลับข้อมูลบนแกน. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | ตั้งค่าเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | ตั้งค่าเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [refreshData()](#refreshData--) | รีเฟรชข้อมูลแผนภูมิโดยโหลดใหม่จากเวิร์กบุ๊กต้นทาง. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่. อ่านอย่างเดียว [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Returns:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

รับชุดข้อมูล. อ่านอย่างเดียว [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Returns:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

รับกลุ่มของชุดข้อมูล. อ่านอย่างเดียว [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) แต่ละกลุ่มของชุดข้อมูลจะมีชุดข้อมูลที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทชุดข้อมูลที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของชุดข้อมูลจะมีชุดข้อมูลที่ถูกพล็อตบนแกนหลักหรือแกนรอง (ไม่ใช้ทั้งสองกรณีในกลุ่มเดียว). ดังนั้นหลักการของการจัดกลุ่มชุดข้อมูลคือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการพล็อตบนแกนหลัก/รอง. 2) กลุ่มของชุดข้อมูลมีคุณสมบัติบางอย่างของชุดข้อมูลที่เป็นสากลสำหรับแต่ละชุดข้อมูลในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries.

**Returns:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรอง หาก property (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น false). อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

หาก property (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น false แล้ว property (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลใน property (\#getCategories.getCategories) นี้จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. หาก property (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น true แล้วข้อมูลใน property (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับชุดข้อมูลรองและข้อมูลใน property (\#getCategories.getCategories) นี้จะใช้สำหรับชุดข้อมูลหลัก.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

หากเป็น false แล้ว property (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลใน property (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. หากเป็น true แล้วข้อมูลใน property (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับชุดข้อมูลรองและข้อมูลใน property (\#getCategories.getCategories) จะใช้สำหรับชุดข้อมูลหลัก. อ่าน/เขียน แบบบูลีน.

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

**Returns:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

หากเป็น false แล้ว property (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลใน property (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. หากเป็น true แล้วข้อมูลใน property (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับชุดข้อมูลรองและข้อมูลใน property (\#getCategories.getCategories) จะใช้สำหรับชุดข้อมูลหลัก. อ่าน/เขียน แบบบูลีน.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

รับหมวดหมู่รองถ้า property (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น true. อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

หาก property (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น false แล้ว property (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลใน property (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. หาก property (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น true แล้วข้อมูลใน property (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับชุดข้อมูลรองและข้อมูลใน property (\#getCategories.getCategories) จะใช้สำหรับชุดข้อมูลหลัก.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

เขียนเวิร์กบุ๊ก Excel ที่บรรจุอยู่ภายในลงในสตรีมในหน่วยความจำ.

**Returns:**
byte[] - คืนค่าอาร์เรย์ของไบต์ที่ประกอบด้วยสำเนาของเวิร์กบุ๊ก Excel ที่บรรจุอยู่ภายใน.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

ตั้งค่าเริ่มต้นเวิร์กบุ๊ก Excel ที่บรรจุอยู่ภายในโดยใช้ค่าที่ผู้ใช้ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| ms | byte[] | สตรีมที่ผู้ใช้ส่งมาซึ่งประกอบด้วยเวิร์กบุ๊ก Excel ทั้งหมด. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

กำหนดช่วงข้อมูลแผนภูมิ. ชุดข้อมูลและหมวดหมู่จะถูกอัปเดตตามช่วงข้อมูลใหม่. หากจำนวนชุดข้อมูลในช่วงข้อมูลมากกว่าจำนวนชุดข้อมูลในแผนภูมิ จะมีการเพิ่มชุดข้อมูลที่มีประเภทเดียวกับชุดข้อมูลสุดท้ายในคอลเลกชันปัจจุบันเข้าที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตรช่วงข้อมูลของเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

รับช่วงข้อมูลแผนภูมิ.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Returns:**
java.lang.String - สูตรช่วงข้อมูลของเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

แสดงแหล่งข้อมูลของแผนภูมิ

**Returns:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

แสดงพาธของเวิร์กบุ๊กภายนอกหากแหล่งข้อมูลเป็นภายนอก, มิฉะนั้นเป็น null

**Returns:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

รับประเภทของเวิร์กบุ๊กที่ฝังอยู่. คืนค่า [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) หาก DataSourceType (\#getDataSourceType.getDataSourceType) คือ [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). อ่านอย่างเดียว [WorkbookType](../../com.aspose.slides/workbooktype).

**Returns:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

สลับข้อมูลบนแกน. ข้อมูลที่แสดงบนแกน X จะย้ายไปยังแกน Y และกลับกัน.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

ตั้งค่าเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะอัปเดตจากเวิร์กบุ๊กเป้าหมาย.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| workbookPath | java.lang.String | พาธไปยังเวิร์กบุ๊กเป้าหมาย |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

ตั้งค่าเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| workbookPath | java.lang.String | พาธไปยังเวิร์กบุ๊กเป้าหมาย |
| updateChartData | boolean | หากค่าเป็น false จะอัปเดตเฉพาะพาธของเวิร์กบุ๊ก. ข้อมูลแผนภูมิจะไม่ถูกโหลดและอัปเดตจากเวิร์กบุ๊กเป้าหมาย. สามารถใช้เมื่อเวิร์กบุ๊กเป้าหมายไม่มีอยู่หรือไม่พร้อมใช้งาน. หากค่าเป็น true ข้อมูลแผนภูมิจะอัปเดตจากเวิร์กบุ๊กเป้าหมาย. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

รีเฟรชข้อมูลแผนภูมิโดยโหลดใหม่จากเวิร์กบุ๊กต้นทาง.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```