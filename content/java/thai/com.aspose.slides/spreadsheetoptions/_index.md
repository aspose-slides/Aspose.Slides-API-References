---
title: SpreadsheetOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงตัวเลือกที่สามารถใช้เพื่อระบุพฤติกรรมเพิ่มเติมของสเปรดชีต
type: docs
url: /th/com.aspose.slides/spreadsheetoptions/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการอิมพลีเมนต์ทั้งหมด:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

แสดงตัวเลือกที่สามารถใช้เพื่อระบุพฤติกรรมเพิ่มเติมของสเปรดชีต
## Constructors

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | สร้างอินสแตนซ์ใหม่ของคลาส [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) |
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับคำนวณฟังก์ชันบางอย่างที่ออกแบบมาสำหรับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS) |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับคำนวณฟังก์ชันบางอย่างที่ออกแบบมาสำหรับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS) |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | หากแหล่งข้อมูลสำหรับแผนภูมิคือเวิร์กบุ๊กภายนอกและไม่พร้อมใช้งาน จะทำการกู้คืนจากแคชของแผนภูมิ |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | หากแหล่งข้อมูลสำหรับแผนภูมิคือเวิร์กบุ๊กภายนอกและไม่พร้อมใช้งาน จะทำการกู้คืนจากแคชของแผนภูมิ |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


สร้างอินสแตนซ์ใหม่ของคลาส [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions)

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับคำนวณฟังก์ชันบางอย่างที่ออกแบบมาสำหรับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS)

**คืนค่า:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับคำนวณฟังก์ชันบางอย่างที่ออกแบบมาสำหรับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


หากแหล่งข้อมูลสำหรับแผนภูมิคือเวิร์กบุ๊กภายนอกและไม่พร้อมใช้งาน จะทำการกู้คืนจากแคชของแผนภูมิ

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


หากแหล่งข้อมูลสำหรับแผนภูมิคือเวิร์กบุ๊กภายนอกและไม่พร้อมใช้งาน จะทำการกู้คืนจากแคชของแผนภูมิ

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |