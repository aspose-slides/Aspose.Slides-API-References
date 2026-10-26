---
title: SpreadsheetOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงตัวเลือกที่ใช้เพื่อกำหนดพฤติกรรมเพิ่มเติมของสเปรดชีต
type: docs
url: /th/com.aspose.slides/spreadsheetoptions/
---
**สืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

แสดงตัวเลือกที่ใช้เพื่อกำหนดพฤติกรรมเพิ่มเติมของสเปรดชีต
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Initializes a new instance of the [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) class. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


สร้างอินสแตนซ์ใหม่ของคลาส [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบให้ใช้กับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS).

**คืนค่า:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบให้ใช้กับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


หากแหล่งข้อมูลของแผนภูมิเป็นสมุดงานภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**คืนค่า:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```


หากแหล่งข้อมูลของแผนภูมิเป็นสมุดงานภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |