---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: एंबेडेड Excel वर्कबुक तक पहुँच प्रदान करता है
type: docs
url: /hi/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

एम्बेडेड Excel वर्कबुक तक पहुँच प्रदान करता है
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | वर्कबुक में सभी फ़ॉर्मूले की गणना करता है और संबंधित सेल मान अपडेट करता है। |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | सेट ऑफ़ सेल्स प्राप्त करता है। |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| [clear(int sheetIndex)](#clear-int-) | शीट पर सभी सेल मान साफ़ करता है |
| [getWorksheets()](#getWorksheets--) | वर्कशीट्स का संग्रह प्राप्त करता है। |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

वर्कबुक में सभी फ़ॉर्मूले की गणना करता है और संबंधित सेल मान अपडेट करता है।

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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

सेट ऑफ़ सेल्स प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | Excel फ़ॉर्मूला जैसे "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | यदि true हो तो यह मेथड छिपे हुए सेल्स के बिना संग्रह लौटाता है। |

**रिटर्न मान:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - सेलों का सेट [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | वर्कशीट का नाम। |
| row | int | पंक्ति। |
| column | int | स्तंभ। |

**रिटर्न मान:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - सेल ऑब्जेक्ट
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का सूचकांक। |
| row | int | पंक्ति। |
| column | int | स्तंभ। |

**रिटर्न मान:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - सेल ऑब्जेक्ट
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का सूचकांक। |
| cellName | java.lang.String | सेल का नाम। |

**रिटर्न मान:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - सेल ऑब्जेक्ट
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का सूचकांक। |
| cellName | java.lang.String | सेल का नाम। |
| value | java.lang.Object | मान। |

**रिटर्न मान:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - सेल ऑब्जेक्ट
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का सूचकांक। |
| row | int | पंक्ति। |
| column | int | स्तंभ। |
| value | java.lang.Object | मान। |

**रिटर्न मान:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - सेल ऑब्जेक्ट
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

शीट पर सभी सेल मान साफ़ करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sheetIndex | int | शीट का सूचकांक। |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
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

**रिटर्न मान:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)