---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: แทนข้อมูลที่ใช้ในการพล็อตแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

แทนข้อมูลที่ใช้ในการพล็อตแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ. |
| [getSeries()](#getSeries--) | รับซีรีส์. |
| [getSeriesGroups()](#getSeriesGroups--) | รับกลุ่มของซีรีส์. |
| [getCategories()](#getCategories--) | รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองหากคุณสมบัติ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็นค่า false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | หากเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะถูกใช้ทั้งสำหรับซีรีส์หลักและรอง. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | หากเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะถูกใช้ทั้งสำหรับซีรีส์หลักและรอง. |
| [getSecondaryCategories()](#getSecondaryCategories--) | รับหมวดหมู่รองหากคุณสมบัติ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็นค่า true. |
| [readWorkbookStream()](#readWorkbookStream--) | เขียนเวิร์กบุค Excel ที่บรรจุภายในไปยังสตรีมในหน่วยความจำ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | กำหนดค่าเริ่มต้นเวิร์กบุค Excel ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ. |
| [setRange(String formula)](#setRange-java.lang.String-) | ตั้งช่วงข้อมูลของแผนภูมิ. |
| [getRange()](#getRange--) | รับช่วงข้อมูลของแผนภูมิ. |
| [getDataSourceType()](#getDataSourceType--) | แทนแหล่งข้อมูลของแผนภูมิ |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | แทนพาธของเวิร์กบุคภายนอกหากแหล่งข้อมูลเป็นภายนอก, หากไม่เป็นจะเป็น null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | รับประเภทของเวิร์กบุคที่ฝังอยู่. |
| [switchRowColumn()](#switchRowColumn--) | สลับข้อมูลข้ามแกน. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | ตั้งค่าเวิร์กบุคภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | ตั้งค่าเวิร์กบุคภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ. อ่านอย่างเดียว [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**คืนค่า:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

รับซีรีส์. อ่านอย่างเดียว [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**คืนค่า:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

รับกลุ่มของซีรีส์. อ่านอย่างเดียว [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

1) แต่ละกลุ่มของซีรีส์ประกอบด้วยซีรีส์ที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของซีรีส์ยังมีซีรีส์ที่ถูกพล็อตบนแกนหลักหรือแกนรอง (ไม่ใช่ทั้งสองอย่างในหนึ่งกลุ่ม). ดังนั้นหลักการของการจัดกลุ่มซีรีส์คือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการพล็อตหลัก/รอง. 2) กลุ่มของซีรีส์มีบางคุณสมบัติของซีรีส์ที่เป็นทั่วไปสำหรับแต่ละซีรีส์ในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries.

**คืนค่า:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองหากคุณสมบัติ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็นค่า false). อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

หากเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะถูกใช้ทั้งสำหรับซีรีส์หลักและรอง. หากเป็น true แล้วข้อมูลในคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับซีรีส์รองและข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้สำหรับซีรีส์หลัก.

**คืนค่า:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

หากเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะถูกใช้ทั้งสำหรับซีรีส์หลักและรอง. หากเป็น true แล้วข้อมูลในคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับซีรีส์รองและข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้สำหรับซีรีส์หลัก. อ่าน/เขียน boolean.

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
public abstract void setUseSecondaryCategories(boolean value)
```

หากเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะถูกใช้ทั้งสำหรับซีรีส์หลักและรอง. หากเป็น true แล้วข้อมูลในคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับซีรีส์รองและข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้สำหรับซีรีส์หลัก. อ่าน/เขียน boolean.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

รับหมวดหมู่รองหากคุณสมบัติ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็นค่า true. อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

หากเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะถูกใช้ทั้งสำหรับซีรีส์หลักและรอง. หากเป็น true แล้วข้อมูลในคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับซีรีส์รองและข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้สำหรับซีรีส์หลัก.

**คืนค่า:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

เขียนเวิร์กบุค Excel ที่บรรจุภายในไปยังสตรีมในหน่วยความจำ.

**คืนค่า:**
byte[] - คืนค่าอาเรย์ของไบต์ที่มีสำเนาของเวิร์กบุค Excel ที่บรรจุภายใน.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

กำหนดค่าเริ่มต้นเวิร์กบุค Excel ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | สตรีมที่ผู้ใช้ระบุซึ่งบรรจุเวิร์กบุค Excel ทั้งหมด. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

ตั้งช่วงข้อมูลของแผนภูมิ. ซีรีส์และหมวดหมู่จะถูกอัปเดตตามช่วงข้อมูลใหม่. หากจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในข้อมูลแผนภูมิแล้ว ซีรีส์เพิ่มเติมที่มีประเภทเดียวกับซีรีส์สุดท้ายในคอลเลกชันปัจจุบันจะถูกเพิ่มไปที่ท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | สูตรช่วงข้อมูลของเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

รับช่วงข้อมูลของแผนภูมิ.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```


**คืนค่า:**
java.lang.String - สูตรช่วงข้อมูลของเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

แทนแหล่งข้อมูลของแผนภูมิ

**คืนค่า:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

แทนพาธของเวิร์กบุคภายนอกหากแหล่งข้อมูลเป็นภายนอก, หากไม่เป็นจะเป็น null

**คืนค่า:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

รับประเภทของเวิร์กบุคที่ฝังอยู่. คืนค่า [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) หาก DataSourceType (\#getDataSourceType.getDataSourceType) เป็น [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). อ่านอย่างเดียว [WorkbookType](../../com.aspose.slides/workbooktype).

**คืนค่า:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

สลับข้อมูลข้ามแกน. ข้อมูลที่แสดงบนแกน X จะย้ายไปยังแกน Y และในทางกลับกัน.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

ตั้งค่าเวิร์กบุคภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะถูกอัปเดตจากเวิร์กบุคเป้าหมาย.

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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | พาธไปยังเวิร์กบุคเป้าหมาย |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

ตั้งค่าเวิร์กบุคภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ.

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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | พาธไปยังเวิร์กบุคเป้าหมาย |
| updateChartData | boolean | หากค่าเป็น false จะอัปเดตเฉพาะพาธของเวิร์กบุค. ข้อมูลแผนภูมิจะไม่ถูกโหลดและอัปเดตจากเวิร์กบุคเป้าหมาย. สามารถใช้ได้เมื่อเวิร์กบุคเป้าหมายไม่มีอยู่หรือไม่สามารถเข้าถึงได้. หากค่าเป็น true ข้อมูลแผนภูมิจะถูกอัปเดตจากเวิร์กบุคเป้าหมาย. |