---
title: ChartData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนข้อมูลที่ใช้สำหรับการพล็อตแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartdata/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

แทนข้อมูลที่ใช้สำหรับการพล็อตแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | รับตัวสร้างเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ. |
| [getSeries()](#getSeries--) | รับซีรีส์. |
| [getSeriesGroups()](#getSeriesGroups--) | รับกลุ่มของซีรีส์. |
| [getCategories()](#getCategories--) | รับประเภทหลัก (หรือทั้งประเภทหลักและประเภทรองหากคุณสมบัติ #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | หากเป็น false แล้วคุณสมบัติ #getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | หากเป็น false แล้วคุณสมบัติ #getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง. |
| [getSecondaryCategories()](#getSecondaryCategories--) | รับประเภทรองหากคุณสมบัติ #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น true. |
| [readWorkbookStream()](#readWorkbookStream--) | เขียน workbook ของ Excel ที่บรรจุภายในลงในสตรีมในหน่วยความจำ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | เริ่มต้น workbook ของ Excel ที่บรรจุภายในด้วยค่าที่ผู้ใช้กำหนด. |
| [getDataSourceType()](#getDataSourceType--) | แทนพาธของ workbook ภายนอกหากเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | แทนแหล่งข้อมูลของแผนภูมิ. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | รับประเภทของ workbook ที่ฝังอยู่. |
| [getRange()](#getRange--) | รับช่วงข้อมูลของแผนภูมิ. |
| [setRange(String formula)](#setRange-java.lang.String-) | ตั้งค่าช่วงข้อมูลของแผนภูมิ. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [switchRowColumn()](#switchRowColumn--) | สลับข้อมูลระหว่างแกน. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

รับตัวสร้างเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ. อ่านอย่างเดียว [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**ผลลัพธ์:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

รับซีรีส์. อ่านอย่างเดียว [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**ผลลัพธ์:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

รับกลุ่มของซีรีส์. อ่านอย่างเดียว [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) แต่ละกลุ่มของซีรีส์จะประกอบด้วยซีรีส์ที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของซีรีส์จะมีซีรีส์ที่วาดบนแกนหลักหรือบนแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียว). ดังนั้นหลักการของการจัดกลุ่มซีรีส์คือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการวาดบนแกนหลัก/รอง.

**ผลลัพธ์:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

รับประเภทหลัก (หรือทั้งประเภทหลักและประเภทรองหากคุณสมบัติ #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false). อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

หากคุณสมบัติ #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false แล้วคุณสมบัติ (#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง. หากคุณสมบัติเป็น true แล้วข้อมูลในคุณสมบัติ (#getSecondaryCategories.getSecondaryCategories) จะใช้สำหรับซีรีส์รองและข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้สำหรับซีรีส์หลัก.

**ผลลัพธ์:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

หากเป็น false แล้วคุณสมบัติ #getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง. หากเป็น true แล้วข้อมูลในคุณสมบัติ #getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้สำหรับซีรีส์หลัก. อ่าน/เขียน boolean.

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

**ผลลัพธ์:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

หากเป็น false แล้วคุณสมบัติ #getSecondaryCategories.getSecondaryCategories จะคืนค่า null และข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง. หากเป็น true แล้วข้อมูลในคุณสมบัติ #getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้สำหรับซีรีส์หลัก. อ่าน/เขียน boolean.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

รับประเภทรองหากคุณสมบัติ #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น true. อ่านอย่างเดียว [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

หากคุณสมบัติ #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) เป็น false แล้วคุณสมบัติ (#getSecondaryCategories.getSecondaryCategories) จะคืนค่า null และข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง. หากเป็น true แล้วข้อมูลในคุณสมบัติ #getSecondaryCategories.getSecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลในคุณสมบัติ #getCategories.getCategories จะใช้สำหรับซีรีส์หลัก.

**ผลลัพธ์:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

เขียน workbook ของ Excel ที่บรรจุภายในลงในสตรีมในหน่วยความจำ.

**ผลลัพธ์:**
byte[] - คืนค่าตัวอย่างของอาเรย์ไบต์ที่มีสำเนาของ workbook ของ Excel ที่บรรจุภายใน.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

เริ่มต้น workbook ของ Excel ที่บรรจุภายในด้วยค่าที่ผู้ใช้กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ms | byte[] | สตรีมที่ผู้ใช้กำหนดซึ่งมี workbook ของ Excel ทั้งหมด. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

แทนพาธของ workbook ภายนอกหากเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น null.

**ผลลัพธ์:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

แทนแหล่งข้อมูลของแผนภูมิ.

**ผลลัพธ์:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

รับประเภทของ workbook ที่ฝังอยู่. คืนค่า [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) หาก DataSourceType (#getDataSourceType.getDataSourceType) เป็น [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). อ่านอย่างเดียว [WorkbookType](../../com.aspose.slides/workbooktype).

**ผลลัพธ์:**
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

**ผลลัพธ์:**
java.lang.String - สูตรช่วงข้อมูลของเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

ตั้งค่าช่วงข้อมูลของแผนภูมิ. ซีรีส์และประเภทจะอัปเดตตามช่วงข้อมูลใหม่. หากจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในแผนภูมิ จะเพิ่มซีรีส์เพิ่มเติมที่มีประเภทเดียวกับซีรีส์สุดท้ายในคอลเลกชันปัจจุบันไปยังท้ายคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตรช่วงข้อมูลของเซลล์. ตัวอย่าง: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

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
| workbookPath | java.lang.String | พาธไปยัง workbook เป้าหมาย |

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
| workbookPath | java.lang.String | พาธไปยัง workbook เป้าหมาย |
| updateChartData | boolean | หากค่าเป็น false จะอัปเดตเฉพาะพาธของ workbook เท่านั้น. ข้อมูลแผนภูมิจะไม่ถูกโหลดและอัปเดตจาก workbook เป้าหมาย. สามารถใช้เมื่อ workbook เป้าหมายไม่มีอยู่หรือไม่พร้อมใช้งาน. หากค่าเป็น true ข้อมูลแผนภูมิจะอัปเดตจาก workbook เป้าหมาย. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

สลับข้อมูลระหว่างแกน. ข้อมูลที่แสดงบนแกน X จะย้ายไปยังแกน Y และในทิศทางตรงกันข้าม.