---
title: ChartDataWorkbook
second_title: อ้างอิง API Java ของ Aspose.Slides สำหรับ Android
description: ให้การเข้าถึงเวิร์กบุ๊ก Excel ที่ฝังอยู่
type: docs
url: /th/com.aspose.slides/chartdataworkbook/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำมาใช้งานทั้งหมด:**  
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)  
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

ให้การเข้าถึงเวิร์กบุ๊ก Excel ที่ฝังอยู่
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | รับคอลเลกชันของเวิร์กชีต |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | รับชุดของเซลล์ |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ |
| [clear(int sheetIndex)](#clear-int-) | ล้างค่าของเซลล์ทั้งหมดในแผ่น |
| [calculateFormulas()](#calculateFormulas--) | คำนวณสูตรทั้งหมดในเวิร์กบุ๊กและอัปเดตค่าของเซลล์ที่สอดคล้อง |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

รับคอลเลกชันของเวิร์กชีต

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

**ผลลัพธ์:**  
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

รับชุดของเซลล์

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตร Excel เช่น "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | หากเป็น true เมธอดจะส่งคืนคอลเลกชันที่ไม่มีเซลล์ที่ซ่อนอยู่. |

**ผลลัพธ์:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของเวิร์กชีท |
| row | int | แถว |
| column | int | คอลัมน์ |

**ผลลัพธ์:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของเวิร์กชีท |
| row | int | แถว |
| column | int | คอลัมน์ |

**ผลลัพธ์:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของเวิร์กชีท |
| cellName | java.lang.String | ชื่อของเซลล์ |

**ผลลัพธ์:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของเวิร์กชีท |
| cellName | java.lang.String | ชื่อของเซลล์ |
| value | java.lang.Object | ค่าที่ต้องการตั้ง |

**ผลลัพธ์:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของเวิร์กชีท |
| row | int | แถว |
| column | int | คอลัมน์ |
| value | java.lang.Object | ค่าที่ต้องการตั้ง |

**ผลลัพธ์:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

ล้างค่าของเซลล์ทั้งหมดในแผ่น

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| sheetIndex | int | ดัชนีของชีต |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

คำนวณสูตรทั้งหมดในเวิร์กบุ๊กและอัปเดตค่าของเซลล์ที่สอดคล้อง

--------------------

> ```
> ตัวอย่างแสดงวิธีการกำหนดสูตรให้กับเซลล์และคำนวณค่า ค่าในเซลล์ "B4" ถูกตั้งเป็น 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```