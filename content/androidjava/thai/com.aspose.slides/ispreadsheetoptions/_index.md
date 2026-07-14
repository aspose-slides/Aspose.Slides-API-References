---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงตัวเลือกที่สามารถใช้เพื่อระบุพฤติกรรมเพิ่มเติมของสเปรดชีต.
type: docs
url: /th/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

แสดงตัวเลือกที่สามารถใช้เพื่อระบุพฤติกรรมเพิ่มเติมของสเปรดชีต.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบมาสำหรับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบมาสำหรับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | หากแหล่งข้อมูลของแผนภูมิเป็นเวิร์กบุ๊กภายนอกและไม่มีอยู่ ระบบจะกู้คืนจากแคชของแผนภูมิ. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | หากแหล่งข้อมูลของแผนภูมิเป็นเวิร์กบุ๊กภายนอกและไม่มีอยู่ ระบบจะกู้คืนจากแคชของแผนภูมิ. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบมาสำหรับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS).

**ผลลัพธ์:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบมาสำหรับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

หากแหล่งข้อมูลของแผนภูมิเป็นเวิร์กบุ๊กภายนอกและไม่มีอยู่ ระบบจะกู้คืนจากแคชของแผนภูมิ.

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

**ผลลัพธ์:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

หากแหล่งข้อมูลของแผนภูมิเป็นเวิร์กบุ๊กภายนอกและไม่มีอยู่ ระบบจะกู้คืนจากแคชของแผนภูมิ.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |