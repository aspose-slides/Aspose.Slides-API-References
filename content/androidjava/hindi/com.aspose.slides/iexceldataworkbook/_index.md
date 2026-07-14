---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: सामान्य उपयोग के लिए Excel डेटा तक पहुंच प्रदान करने वाले वर्कबुक का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

सामान्य उपयोग के लिए Excel डेटा तक पहुंच प्रदान करने वाले वर्कबुक का प्रतिनिधित्व करता है.
## विधाएँ

| मेथड | विवरण |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | वर्कबुक से उन सभी कोशिकाओं का संग्रह प्राप्त करता है जो निर्दिष्ट सूत्र से मेल खाती हैं। |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | निर्दिष्ट वर्कशीट से उसकी अनुक्रमणिका और कोशिका निर्देशांक के आधार पर एक कोशिका प्राप्त करता है। |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | निर्दिष्ट वर्कशीट से उसके नाम और कोशिका निर्देशांक के आधार पर एक कोशिका प्राप्त करता है। |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | निर्दिष्ट वर्कशीट से उसकी अनुक्रमणिका और Excel-शैली के कोशिका नाम (उदा., "B2") के आधार पर एक कोशिका प्राप्त करता है। |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | निर्दिष्ट वर्कशीट से Excel-शैली के कोशिका नाम (उदा., "B2") के आधार पर एक कोशिका प्राप्त करता है। |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Excel वर्कबुक की निर्दिष्ट वर्कशीट में सभी चार्ट की अनुक्रमणिका और नामों को सम्मिलित करने वाला शब्दकोश प्राप्त करता है। |
| [getWorksheetNames()](#getWorksheetNames--) | Excel वर्कबुक में सम्मिलित सभी वर्कशीटों के नाम प्राप्त करता है। |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

वर्कबुक से उन सभी कोशिकाओं का संग्रह प्राप्त करता है जो निर्दिष्ट सूत्र से मेल खाती हैं।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //आउटपुट: 5
>  ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | लक्ष्य कोशिकाओं को पहचानने के लिये उपयोग किया जाता है सूत्र या रेंज अभिव्यक्ति (उदा., "Sheet1!A1:B3")। |
| skipHiddenCells | boolean | यदि true है, तो छिपी हुई कोशिकाएँ (उदा., छिपी हुई पंक्तियों या स्तंभों में) परिणाम से बाहर रखी जाएँगी। |

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - केवल-पढ़ने योग्य सूची जो निर्दिष्ट सूत्र से मेल खाती कोशिकाओं को सम्मिलित करती है।
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

निर्दिष्ट वर्कशीट से उसकी अनुक्रमणिका और कोशिका निर्देशांक के आधार पर एक कोशिका प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
>  ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का शून्य-आधारित अनुक्रमणिका। |
| row | int | कोशिका की शून्य-आधारित पंक्ति अनुक्रमणिका। |
| column | int | कोशिका की शून्य-आधारित स्तंभ अनुक्रमणिका। |

**रिटर्न मान:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर मौजूद कोशिका।
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

निर्दिष्ट वर्कशीट से उसके नाम और कोशिका निर्देशांक के आधार पर एक कोशिका प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | वर्कशीट का नाम। |
| row | int | कोशिका की शून्य-आधारित पंक्ति अनुक्रमणिका। |
| column | int | कोशिका की शून्य-आधारित स्तंभ अनुक्रमणिका। |

**रिटर्न मान:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर मौजूद कोशिका।
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

निर्दिष्ट वर्कशीट से उसकी अनुक्रमणिका और Excel-शैली के कोशिका नाम (उदा., "B2") के आधार पर एक कोशिका प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का शून्य-आधारित अनुक्रमणिका। |
| cellName | java.lang.String | Excel-शैली की कोशिका संदर्भ (उदा., "A1", "C5")। |

**रिटर्न मान:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर मौजूद कोशिका।
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Excel-शैली के कोशिका नाम (उदा., "B2") के आधार पर निर्दिष्ट वर्कशीट से एक कोशिका प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | वर्कशीट का नाम। |
| cellName | java.lang.String | Excel-शैली की कोशिका संदर्भ (उदा., "A1", "C5")। |

**रिटर्न मान:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर मौजूद कोशिका।
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Excel वर्कबुक की निर्दिष्ट वर्कशीट में सभी चार्ट की अनुक्रमणिका और नामों को सम्मिलित करने वाला शब्दकोश प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | चार्ट खोजने के लिये वर्कशीट का नाम। |

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - एक शब्दकोश जहाँ कुंजी चार्ट की अनुक्रमणिका है और मान चार्ट का नाम।
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Excel वर्कबुक में सम्मिलित सभी वर्कशीटों के नाम प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - वर्कशीट नामों की सूची