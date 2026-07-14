---
title: ExcelWorkbookImporter
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस द्वारा
description: एक्सेल वर्कबुक से सामग्री को प्रस्तुति में आयात करने की कार्यक्षमता प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/excelworkbookimporter/
---
**विरासत:**  
java.lang.Object  
```
public class ExcelWorkbookImporter
```

एक्सेल वर्कबुक से सामग्री को प्रस्तुति में आयात करने की कार्यक्षमता प्रदान करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | निर्दिष्ट एक्सेल वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है। |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | निर्दिष्ट एक्सेल वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है। |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | निर्दिष्ट एक्सेल वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है। |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | निर्दिष्ट एक्सेल वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है। |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | निर्दिष्ट एक्सेल वर्कबुक से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है। |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | निर्दिष्ट एक्सेल वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है। |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | निर्दिष्ट एक्सेल वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है। |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

निर्दिष्ट एक्सेल वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | शेप कलेक्शन जिसमें चार्ट जोड़ा जाएगा। |
| x | float | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | float | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | एक्सेल वर्कबुक। |
| worksheetName | java.lang.String | वह वर्कशीट नाम जिसमें चार्ट है। |
| chartIndex | int | इन्सर्ट किए जाने वाले चार्ट शेप का शून्य-आधारित अनुक्रमणिका। यह अनुक्रमणिका [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) विधि का उपयोग करके प्राप्त की जा सकती है। |
| embedAllWorkbook | boolean | यदि true हो, तो पूरी वर्कबुक चार्ट में एम्बेड होगी; यदि false हो, तो केवल चार्ट डेटा एम्बेड होगा। |

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart) - शेप कलेक्शन में जोड़ा गया चार्ट।

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

निर्दिष्ट एक्सेल वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | शेप कलेक्शन जिसमें चार्ट जोड़ा जाएगा। |
| x | float | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | float | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | एक्सेल वर्कबुक। |
| worksheetName | java.lang.String | वह वर्कशीट नाम जिसमें चार्ट है। |
| chartName | java.lang.String | जोड़ने के लिए चार्ट का नाम। |
| embedAllWorkbook | boolean | यदि true हो, तो पूरी वर्कबुक चार्ट में एम्बेड होगी; यदि false हो, तो केवल चार्ट डेटा एम्बेड होगा। |

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart) - शेप कलेक्शन में जोड़ा गया चार्ट।

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

निर्दिष्ट एक्सेल वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | शेप कलेक्शन जिसमें चार्ट जोड़ा जाएगा। |
| x | float | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | float | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbookStream | java.io.InputStream | वर्कबुक डेटा युक्त स्ट्रीम। |
| worksheetName | java.lang.String | वह वर्कशीट नाम जिसमें चार्ट है। |
| chartName | java.lang.String | जोड़ने के लिए चार्ट का नाम। |
| embedAllWorkbook | boolean | यदि true हो, तो पूरी वर्कबुक चार्ट में एम्बेड होगी; यदि false हो, तो केवल चार्ट डेटा एम्बेड होगा। |

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart) - शेप कलेक्शन में जोड़ा गया चार्ट।

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

निर्दिष्ट एक्सेल वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | शेप कलेक्शन जिसमें चार्ट जोड़ा जाएगा। |
| x | float | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | float | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbookPath | java.lang.String | वह फ़ाइल पथ जिसमें चार्ट वाला वर्कबुक है। |
| worksheetName | java.lang.String | वह वर्कशीट नाम जिसमें चार्ट है। |
| chartName | java.lang.String | जोड़ने के लिए चार्ट का नाम। |
| embedWorkbook | boolean | यदि true हो, तो वर्कबुक चार्ट में एम्बेड होगी; यदि false हो, तो चार्ट बाहरी वर्कबुक से लिंक करेगा। |

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart) - शेप कलेक्शन में जोड़ा गया चार्ट।

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

निर्दिष्ट एक्सेल वर्कबुक से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | शेप कलेक्शन जिसमें तालिका जोड़ी जाएगी। |
| x | float | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | float | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | एक्सेल वर्कबुक। |
| worksheetName | java.lang.String | वह वर्कशीट नाम जिसमें तालिका है। |
| cellRange | java.lang.String | वह सेल रेंज जो तालिका को परिभाषित करती है (उदाहरण के लिए, "A1:D10")। |

**रिटर्न:**  
[ITable](../../com.aspose.slides/itable) - शेप कलेक्शन में जोड़ी गई तालिका।

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

निर्दिष्ट एक्सेल वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | शेप कलेक्शन जिसमें तालिका जोड़ी जाएगी। |
| x | float | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | float | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbookPath | java.lang.String | एक्सेल वर्कबुक फ़ाइल का पथ। |
| worksheetName | java.lang.String | वह वर्कशीट नाम जिसमें तालिका है। |
| cellRange | java.lang.String | वह सेल रेंज जो तालिका को परिभाषित करती है (उदाहरण के लिए, "A1:D10")। |

**रिटर्न:**  
[ITable](../../com.aspose.slides/itable) - शेप कलेक्शन में जोड़ी गई तालिका।

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

निर्दिष्ट एक्सेल वर्कबुक फ़ाइल से एक तालिका प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | शेप कलेक्शन जिसमें तालिका जोड़ी जाएगी। |
| x | float | तालिका को स्थित करने के लिए X निर्देशांक। |
| y | float | तालिका को स्थित करने के लिए Y निर्देशांक। |
| workbookStream | java.io.InputStream | वर्कबुक डेटा युक्त स्ट्रीम। |
| worksheetName | java.lang.String | वह वर्कशीट नाम जिसमें तालिका है। |
| cellRange | java.lang.String | वह सेल रेंज जो तालिका को परिभाषित करती है (उदाहरण के लिए, "A1:D10")। |

**रिटर्न:**  
[ITable](../../com.aspose.slides/itable) - शेप कलेक्शन में जोड़ी गई तालिका।