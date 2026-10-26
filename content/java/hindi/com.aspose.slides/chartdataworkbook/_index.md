---
title: ChartDataWorkbook
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एम्बेडेड एक्सेल वर्कबुक तक पहुंच प्रदान करता है
type: docs
url: /hi/com.aspose.slides/chartdataworkbook/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)  
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

एम्बेडेड एक्सेल वर्कबुक तक पहुंच प्रदान करता है  

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | वर्कशीट्स का संग्रह प्राप्त करता है। |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | cells का सेट प्राप्त करता है। |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है |
| [clear(int sheetIndex)](#clear-int-) | शीट पर सभी cells मान साफ़ करें |
| [calculateFormulas()](#calculateFormulas--) | वर्कबुक में सभी formulas की गणना करता है और संबंधित cells मान अपडेट करता है। |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

वर्कशीट्स का संग्रह प्राप्त करता है।

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

**रिटर्न:**  
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

cells का सेट प्राप्त करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | Excel सूत्र जैसा "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | यदि true हो तो मेथड छुपे हुए cells के बिना संग्रह वापस करता है। |

**रिटर्न:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | वर्कशीट का नाम। |
| row | int | The row. |
| column | int | The column. |

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का इंडेक्स। |
| row | int | The row. |
| column | int | The column. |

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का इंडेक्स। |
| cellName | java.lang.String | cell का नाम। |

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का इंडेक्स। |
| cellName | java.lang.String | cell का नाम। |
| value | java.lang.Object | मान। |

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला cell प्राप्त करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का इंडेक्स। |
| row | int | The row. |
| column | int | The column. |
| value | java.lang.Object | मान। |

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

शीट पर सभी cells मान साफ़ करें

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sheetIndex | int | शीट का इंडेक्स। |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

वर्कबुक में सभी formulas की गणना करता है और संबंधित cells मान अपडेट करता है।

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
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