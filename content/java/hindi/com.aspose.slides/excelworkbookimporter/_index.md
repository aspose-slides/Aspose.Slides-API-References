---
title: ExcelWorkbookImporter
second_title: Aspose.Slides for Java API संदर्भ
description: एक Excel वर्कबुक से सामग्री को प्रस्तुति में आयात करने की कार्यक्षमता प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/excelworkbookimporter/
---
**विरासत:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

एक Excel वर्कबुक से सामग्री को एक प्रस्तुति में आयात करने की कार्यक्षमता प्रदान करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है। |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है। |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है। |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है। |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | निर्दिष्ट Excel वर्कबुक से एक तालिका प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है। |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | निर्दिष्ट Excel वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है। |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | निर्दिष्ट Excel वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है। |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | चार्ट जोड़ने के लिए shape संग्रह। |
| x | float | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | float | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel वर्कबुक। |
| worksheetName | java.lang.String | चार्ट वाले worksheet का नाम। |
| chartIndex | int | चार्ट shape को सम्मिलित करने के लिए शून्य-आधारित सूचकांक। यह सूचकांक [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) विधि द्वारा प्राप्त किया जा सकता है। |
| embedAllWorkbook | boolean | यदि सत्य है, तो संपूर्ण workbook चार्ट में एम्बेड हो जाएगा; यदि असत्य है, तो केवल चार्ट डेटा एम्बेड होगा। |

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart) - shape संग्रह में जोड़ा गया चार्ट।

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | चार्ट जोड़ने के लिए shape संग्रह। |
| x | float | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | float | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel वर्कबुक। |
| worksheetName | java.lang.String | चार्ट वाले worksheet का नाम। |
| chartName | java.lang.String | जोड़ा जाने वाले चार्ट का नाम। |
| embedAllWorkbook | boolean | यदि सत्य है, तो संपूर्ण workbook चार्ट में एम्बेड हो जाएगा; यदि असत्य है, तो केवल चार्ट डेटा एम्बेड होगा। |

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart) - shape संग्रह में जोड़ा गया चार्ट।

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | चार्ट जोड़ने के लिए shape संग्रह। |
| x | float | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | float | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbookStream | java.io.InputStream | वर्कबुक डेटा वाला स्ट्रीम। |
| worksheetName | java.lang.String | चार्ट वाले worksheet का नाम। |
| chartName | java.lang.String | जोड़ा जाने वाले चार्ट का नाम। |
| embedAllWorkbook | boolean | यदि सत्य है, तो संपूर्ण workbook चार्ट में एम्बेड हो जाएगा; यदि असत्य है, तो केवल चार्ट डेटा एम्बेड होगा। |

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart) - shape संग्रह में जोड़ा गया चार्ट।

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | चार्ट जोड़ने के लिए shape संग्रह। |
| x | float | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | float | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbookPath | java.lang.String | चार्ट वाला वर्कबुक फ़ाइल पथ। |
| worksheetName | java.lang.String | चार्ट वाले worksheet का नाम। |
| chartName | java.lang.String | जोड़ा जाने वाले चार्ट का नाम। |
| embedWorkbook | boolean | यदि सत्य है, तो workbook चार्ट में एम्बेड होगा; यदि असत्य है, तो चार्ट बाहरी workbook से जुड़ा रहेगा। |

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart) - shape संग्रह में जोड़ा गया चार्ट।

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

निर्दिष्ट Excel वर्कबुक से एक तालिका प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | तालिका जोड़ने के लिए shape संग्रह। |
| x | float | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | float | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel वर्कबुक। |
| worksheetName | java.lang.String | तालिका वाले worksheet का नाम। |
| cellRange | java.lang.String | तालिका को परिभाषित करने वाला सेल रेंज (उदाहरण के लिए, "A1:D10")। |

**रिटर्न:**
[ITable](../../com.aspose.slides/itable) - shape संग्रह में जोड़ी गई तालिका।

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

निर्दिष्ट Excel वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | तालिका जोड़ने के लिए shape संग्रह। |
| x | float | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | float | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbookPath | java.lang.String | Excel वर्कबुक फ़ाइल का पथ। |
| worksheetName | java.lang.String | तालिका वाले worksheet का नाम। |
| cellRange | java.lang.String | तालिका को परिभाषित करने वाला सेल रेंज (उदाहरण के लिए, "A1:D10")। |

**रिटर्न:**
[ITable](../../com.aspose.slides/itable) - shape संग्रह में जोड़ी गई तालिका।

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

निर्दिष्ट Excel वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्धारित निर्देशांक पर दिए गए shape संग्रह के अंत में इसे जोड़ता है।

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | तालिका जोड़ने के लिए shape संग्रह। |
| x | float | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | float | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbookStream | java.io.InputStream | वर्कबुक डेटा वाला स्ट्रीम। |
| worksheetName | java.lang.String | तालिका वाले worksheet का नाम। |
| cellRange | java.lang.String | तालिका को परिभाषित करने वाला सेल रेंज (उदाहरण के लिए, "A1:D10")। |

**रिटर्न:**
[ITable](../../com.aspose.slides/itable) - shape संग्रह में जोड़ी गई तालिका।