---
title: ChartData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นข้อมูลที่ใช้สำหรับการวาดแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartdata/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Represents data used for a chart plotting.
## เมธอด

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ. |
| [getSeries()](#getSeries--) | รับซีรีส์. |
| [getSeriesGroups()](#getSeriesGroups--) | รับกลุ่มของซีรีส์. |
| [getCategories()](#getCategories--) | รับประเภทหลัก (หรือทั้งประเภทหลักและประเภทรองหาก property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | หากเป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | หากเป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. |
| [getSecondaryCategories()](#getSecondaryCategories--) | รับประเภทรองหาก property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น true. |
| [readWorkbookStream()](#readWorkbookStream--) | เขียน Excel workbook ที่บรรจุอยู่ภายในไปยังสตรีมในหน่วยความจำ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | เริ่มต้น Excel workbook ที่บรรจุอยู่ภายในด้วยค่าที่ผู้ใช้ระบุ. |
| [getDataSourceType()](#getDataSourceType--) | แสดงเส้นทางของ workbook ภายนอกหากเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | แสดงแหล่งข้อมูลของแผนภูมิ. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | รับประเภทของ workbook ที่ฝังอยู่. |
| [getRange()](#getRange--) | รับช่วงข้อมูลของแผนภูมิ. |
| [setRange(String formula)](#setRange-java.lang.String-) | ตั้งค่าช่วงข้อมูลของแผนภูมิ. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [refreshData()](#refreshData--) | รีเฟรชข้อมูลแผนภูมิโดยโหลดใหม่จาก workbook แหล่งที่มา. |
| [switchRowColumn()](#switchRowColumn--) | สลับข้อมูลข้ามแกน. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```


รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ. อ่านอย่างเดียว [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**ส่งคืน:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```


รับซีรีส์. อ่านอย่างเดียว [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**ส่งคืน:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```


รับกลุ่มของซีรีส์. อ่านอย่างเดียว [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) แต่ละกลุ่มของซีรีส์ประกอบด้วยซีรีส์ที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของซีรีส์ยังรวมซีรีส์ที่ถูกวาดบนแกนหลักหรือแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียว). ดังนั้นหลักการของการจัดกลุ่มซีรีส์คือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการวาดบนแกนหลัก/รอง. 2) กลุ่มของซีรีส์มีคุณสมบัติบางอย่างของซีรีส์ที่เป็นร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายภาพแบบอ่านอย่างเดียวในคลาส ChartSeries.

**ส่งคืน:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```


รับประเภทหลัก (หรือทั้งประเภทหลักและประเภทรองหาก property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false). อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ประเภทที่เกี่ยวข้องคือ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ประเภทที่เกี่ยวข้องคือ series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

หาก property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false แล้ว property (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories นี้จะใช้ทั้งสำหรับซีรีส์หลักและรอง. หาก property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น true แล้วข้อมูลใน property (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับซีรีส์รองและข้อมูลใน property \#getCategories.getCategories นี้จะใช้สำหรับซีรีส์หลัก.

**ส่งคืน:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```


หากเป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า nullและข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. หากเป็น true แล้วข้อมูลใน property \#getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลใน property \#getCategories.getCategories จะใช้สำหรับซีรีส์หลัก. อ่าน/เขียน Boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ประเภทที่เกี่ยวข้องคือ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ประเภทที่เกี่ยวข้องคือ series.getChart().getChartData().getCategories()
>  }
> ```

**ส่งคืน:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```


หากเป็น false แล้ว property \#getSecondaryCategories.getSecondaryCategories จะคืนค่า nullและข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. หากเป็น true แล้วข้อมูลใน property \#getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลใน property \#getCategories.getCategories จะใช้สำหรับซีรีส์หลัก. อ่าน/เขียน Boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ประเภทที่เกี่ยวข้องคือ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ประเภทที่เกี่ยวข้องคือ series.getChart().getChartData().getCategories()
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```


รับประเภทรองหาก property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น true. อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ประเภทที่เกี่ยวข้องคือ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ประเภทที่เกี่ยวข้องคือ series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

หาก property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false แล้ว property (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลใน property \#getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและรอง. หาก property \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น true แล้วข้อมูลใน property (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับซีรีส์รองและข้อมูลใน property \#getCategories.getCategories จะใช้สำหรับซีรีส์หลัก.

**ส่งคืน:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```


เขียน Excel workbook ที่บรรจุอยู่ภายในไปยังสตรีมในหน่วยความจำ.

**ส่งคืน:**
byte[] - ส่งคืนอาร์เรย์ของไบต์ที่มีสำเนาของ Excel workbook ที่บรรจุอยู่ภายใน.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```


เริ่มต้น Excel workbook ที่บรรจุอยู่ภายในด้วยค่าที่ผู้ใช้ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | สตรีมที่ผู้ใช้ให้ซึ่งบรรจุ Excel workbook อย่างเต็ม. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


แสดงเส้นทางของ workbook ภายนอกหากเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น null.

**ส่งคืน:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```


แสดงแหล่งข้อมูลของแผนภูมิ.

**ส่งคืน:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```


รับประเภทของ workbook ที่ฝังอยู่. ส่งคืน [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) หาก DataSourceType (\#getDataSourceType.getDataSourceType) เป็น [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). อ่านอย่างเดียว [WorkbookType](../../com.aspose.slides/workbooktype).

**ส่งคืน:**
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

**ส่งคืน:**
java.lang.String - สูตรช่วงข้อมูลของเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```


ตั้งค่าช่วงข้อมูลของแผนภูมิ. ซีรีส์และประเภทจะได้รับการอัปเดตตามช่วงข้อมูลใหม่. หากจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในข้อมูลแผนภูมิ จะมีการเพิ่มซีรีส์เพิ่มเติมที่มีประเภทเดียวกับซีรีส์สุดท้ายในคอลเลกชันปัจจุบันที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | สูตรช่วงข้อมูลของเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```


ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะได้รับการอัปเดตจาก workbook เป้าหมาย.

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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | เส้นทางไปยัง workbook เป้าหมาย |
| updateChartData | boolean | หากค่าเป็น false จะอัปเดตเฉพาะเส้นทาง workbook เท่านั้น. ข้อมูลแผนภูมิจะไม่ได้รับการโหลดและอัปเดตจาก workbook เป้าหมาย. สามารถใช้ได้เมื่อ workbook เป้าหมายไม่มีหรือไม่พร้อมใช้งาน. หากค่าเป็น true ข้อมูลแผนภูมิจะอัปเดตจาก workbook เป้าหมาย. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```


รีเฟรชข้อมูลแผนภูมิโดยโหลดใหม่จาก workbook แหล่งที่มา.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```


สลับข้อมูลข้ามแกน. ข้อมูลที่แสดงบนแกน X จะย้ายไปที่แกน Y และในทางกลับกัน.