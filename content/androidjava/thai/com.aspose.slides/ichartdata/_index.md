---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: แทนข้อมูลที่ใช้สำหรับการสร้างแผนภูมิ
type: docs
url: /th/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

แทนข้อมูลที่ใช้สำหรับการสร้างแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่. |
| [getSeries()](#getSeries--) | รับชุดข้อมูล. |
| [getSeriesGroups()](#getSeriesGroups--) | รับกลุ่มของชุดข้อมูล. |
| [getCategories()](#getCategories--) | รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองหากคุณสมบัติ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | ถ้าเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | ถ้าเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. |
| [getSecondaryCategories()](#getSecondaryCategories--) | รับหมวดหมู่รองหากคุณสมบัติ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น true. |
| [readWorkbookStream()](#readWorkbookStream--) | เขียน Excel workbook ที่บรรจุภายในลงในสตรีมในหน่วยความจำ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | เริ่มต้น Excel workbook ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ. |
| [setRange(String formula)](#setRange-java.lang.String-) | กำหนดช่วงข้อมูลแผนภูมิ. |
| [getRange()](#getRange--) | รับช่วงข้อมูลแผนภูมิ. |
| [getDataSourceType()](#getDataSourceType--) | แทนแหล่งข้อมูลของแผนภูมิ |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | แทนเส้นทาง workbook ภายนอกหากแหล่งข้อมูลเป็นภายนอก, มิฉะนั้นเป็น null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | รับประเภทของ workbook ที่ฝังอยู่. |
| [switchRowColumn()](#switchRowColumn--) | สลับข้อมูลบนแกน. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่. อ่านอย่างเดียว [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**คืนค่า:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

รับชุดข้อมูล. อ่านอย่างเดียว [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**คืนค่า:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

รับกลุ่มของชุดข้อมูล. อ่านอย่างเดียว [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) แต่ละกลุ่มของชุดข้อมูลประกอบด้วยชุดข้อมูลที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทชุดข้อมูลที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของชุดข้อมูลยังประกอบด้วยชุดข้อมูลที่แสดงบนแกนหลักหรือแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียว). ดังนั้น หลักการของการจัดกลุ่มชุดข้อมูลคือการจัดกลุ่มตามประเภทที่กล่าวมาข้างต้นและตามประเภทการแสดงผลบนแกนหลัก/รอง.

**คืนค่า:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองหากคุณสมบัติ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น false). อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

ถ้า (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัตินี้ (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. ถ้าเป็น true แล้วข้อมูลในคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับชุดข้อมูลรองและข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้สำหรับชุดข้อมูลหลัก.

**คืนค่า:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

ถ้าเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. ถ้าเป็น true แล้วข้อมูลในคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับชุดข้อมูลรองและข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้สำหรับชุดข้อมูลหลัก. อ่าน/เขียน boolean.

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

ถ้าเป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. ถ้าเป็น true แล้วข้อมูลในคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับชุดข้อมูลรองและข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้สำหรับชุดข้อมูลหลัก. อ่าน/เขียน boolean.

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
public abstract IChartCategoryCollection getSecondaryCategories()
```

รับหมวดหมู่รองหากคุณสมบัติ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น true. อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

ถ้า (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) เป็น false แล้วคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. ถ้าเป็น true แล้วข้อมูลในคุณสมบัติ (\#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับชุดข้อมูลรองและข้อมูลในคุณสมบัติ (\#getCategories.getCategories) จะใช้สำหรับชุดข้อมูลหลัก.

**คืนค่า:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

เขียน Excel workbook ที่บรรจุภายในลงในสตรีมในหน่วยความจำ.

**คืนค่า:**
byte[] - คืนค่าอาร์เรย์ของไบต์ที่มีสำเนาของ Excel workbook ที่บรรจุภายใน.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

เริ่มต้น Excel workbook ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ms | byte[] | สตรีมที่ผู้ใช้จัดหาซึ่งประกอบด้วย Excel workbook ทั้งหมด. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

กำหนดช่วงข้อมูลแผนภูมิ. ชุดข้อมูลและหมวดหมู่จะอัพเดตตามช่วงข้อมูลใหม่. หากจำนวนชุดข้อมูลในช่วงข้อมูลมากกว่าจำนวนชุดข้อมูลในแผนภูมิ จะมีการเพิ่มชุดข้อมูลที่มีประเภทเดียวกับชุดข้อมูลสุดท้ายในคอลเลกชันปัจจุบันไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตรช่วงข้อมูลเซลล์ เช่น: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

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

**คืนค่า:**
java.lang.String - สูตรช่วงข้อมูลเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4"

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

แทนเส้นทาง workbook ภายนอกหากแหล่งข้อมูลเป็นภายนอก, มิฉะนั้นเป็น null

**คืนค่า:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

รับประเภทของ workbook ที่ฝังอยู่. คืนค่า [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) หาก DataSourceType (\#getDataSourceType.getDataSourceType) เป็น [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). อ่านอย่างเดียว [WorkbookType](../../com.aspose.slides/workbooktype).

**คืนค่า:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

สลับข้อมูลบนแกน. ข้อมูลที่แสดงบนแกน X จะย้ายไปยังแกน Y และในทางกลับกัน.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะอัพเดตจาก workbook เป้าหมาย.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| workbookPath | java.lang.String | เส้นทางไปยัง workbook เป้าหมาย |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| workbookPath | java.lang.String | เส้นทางไปยัง workbook เป้าหมาย |
| updateChartData | boolean | หากค่าเป็น false จะอัพเดตเฉพาะเส้นทาง workbook เท่านั้น. ข้อมูลแผนภูมิจะไม่ถูกโหลดและอัพเดตจาก workbook เป้าหมาย. สามารถใช้เมื่อ workbook เป้าหมายไม่มีอยู่หรือไม่สามารถเข้าถึงได้. หากค่าเป็น true ข้อมูลแผนภูมิจะอัพเดตจาก workbook เป้าหมาย. |