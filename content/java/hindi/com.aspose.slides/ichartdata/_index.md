---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: चार्ट प्लॉटिंग के लिए उपयोग किए गए डेटा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

चार्ट प्लॉटिंग के लिए उपयोग किए गए डेटा का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | चार्ट श्रृंखला या श्रेणियों के लिए उपयोग किए जाने वाले सेल बनाने के लिए सेल फ़ैक्ट्री प्राप्त करता है। |
| [getSeries()](#getSeries--) | श्रृंखलाओं को प्राप्त करता है। |
| [getSeriesGroups()](#getSeriesGroups--) | श्रृंखलाओं के समूहों को प्राप्त करता है। |
| [getCategories()](#getCategories--) | प्राथमिक श्रेणियों को प्राप्त करता है (या दोनों प्राथमिक और द्वितीयक श्रेणियाँ यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) गुण false है)। |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) गुण null लौटाता है और (\#getCategories.getCategories) गुण में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) गुण null लौटाता है और (\#getCategories.getCategories) गुण में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। |
| [getSecondaryCategories()](#getSecondaryCategories--) | यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) गुण true है तो द्वितीयक श्रेणियों को प्राप्त करता है। |
| [readWorkbookStream()](#readWorkbookStream--) | आंतरिक रूप से सम्मिलित Excel वर्कबुक को मेमोरी में स्थित स्ट्रीम में लिखता है। |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | आंतरिक रूप से सम्मिलित Excel वर्कबुक को उपयोगकर्ता-निर्दिष्ट मूल्य के साथ प्रारम्भ करता है। |
| [setRange(String formula)](#setRange-java.lang.String-) | चार्ट डेटा रेंज सेट करता है। |
| [getRange()](#getRange--) | चार्ट डेटा रेंज को प्राप्त करता है। |
| [getDataSourceType()](#getDataSourceType--) | चार्ट के डेटा स्रोत का प्रतिनिधित्व करता है। |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | यदि डेटा स्रोत बाहरी है तो बाहरी वर्कबुक पथ का प्रतिनिधित्व करता है, अन्यथा null। |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | समाहित वर्कबुक के प्रकार को प्राप्त करता है। |
| [switchRowColumn()](#switchRowColumn--) | डेटा को अक्ष के ऊपर अदला-बदली करता है। |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

चार्ट श्रृंखला या श्रेणियों के लिए उपयोग किए जाने वाले सेल बनाने के लिए सेल फ़ैक्ट्री प्राप्त करता है। केवल पढ़ने योग्य [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)।

**रिटर्न:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

श्रृंखलाओं को प्राप्त करता है। केवल पढ़ने योग्य [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)।

**रिटर्न:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

श्रृंखलाओं के समूहों को प्राप्त करता है। केवल पढ़ने योग्य [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)।

--------------------

1) प्रत्येक श्रृंखला समूह में मिलाए जाने योग्य प्रकारों वाली श्रृंखलाएँ होती हैं। मिलाए जाने योग्य श्रृंखला प्रकारों के समूह को CombinableSeriesTypesGroup enum के साथ परिभाषित और वर्णित किया गया है। साथ ही प्रत्येक श्रृंखला समूह में ऐसी श्रृंखलाएँ होती हैं जो प्राथमिक अक्षों पर या द्वितीयक अक्षों पर प्लॉट की जाती हैं (एक समूह में दोनों मामलों नहीं)। इसलिए, श्रृंखला समूहकरण का सिद्धांत उपरोक्त उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा समूह बनाना है। 2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह की प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties")। ChartSeriesGroup क्लास में "series group properties" पढ़ें/लिखें हैं। प्रत्येक "series group properties" का ChartSeries क्लास में केवल पढ़ने योग्य प्रोजेक्ट हो सकता है।

**रिटर्न:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

प्राथमिक श्रेणियों को प्राप्त करता है (या दोनों प्राथमिक और द्वितीयक श्रेणियाँ यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) गुण false है)। केवल पढ़ने योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) गुण false है तो (\#getSecondaryCategories.getSecondaryCategories) गुण null लौटाता है और इस (\#getCategories.getCategories) गुण में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) गुण true है तो (\#getSecondaryCategories.getSecondaryCategories) गुण में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है और इस (\#getCategories.getCategories) गुण में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग किया जाता है।

**रिटर्न:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) गुण null लौटाता है और (\#getCategories.getCategories) गुण में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। यदि true है तो (\#getSecondaryCategories.getSecondaryCategories) गुण में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है और (\#getCategories.getCategories) गुण में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग किया जाता है। पढ़ें/लिखें बूलियन।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getCategories()
>  }
> ```

**रिटर्न:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) गुण null लौटाता है और (\#getCategories.getCategories) गुण में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। यदि true है तो (\#getSecondaryCategories.getSecondaryCategories) गुण में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है और (\#getCategories.getCategories) गुण में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग किया जाता है। पढ़ें/लिखें बूलियन।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getCategories()
>  }
> ```

**पैरामीटर** | **टाइप** | **विवरण**
--- | --- | ---
value | boolean | 

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

द्वितीयक श्रेणियों को प्राप्त करता है यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) गुण true है। केवल पढ़ने योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) गुण false है तो यह (\#getSecondaryCategories.getSecondaryCategories) गुण null लौटाता है और (\#getCategories.getCategories) गुण में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) गुण true है तो यह (\#getSecondaryCategories.getSecondaryCategories) गुण में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है और (\#getCategories.getCategories) गुण में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग किया जाता है।

**रिटर्न:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

आंतरिक रूप से सम्मिलित Excel वर्कबुक को मेमोरी में स्थित स्ट्रीम में लिखता है।

**रिटर्न:**
byte[] - एक बाइट एरे लौटाता है जिसमें आंतरिक रूप से सम्मिलित Excel वर्कबुक की प्रतिलिपि होती है।

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

आंतरिक रूप से सम्मिलित Excel वर्कबुक को उपयोगकर्ता-निर्दिष्ट मूल्य के साथ प्रारम्भ करता है।

**पैरामीटर** | **टाइप** | **विवरण**
--- | --- | ---
ms | byte[] | उपयोगकर्ता द्वारा प्रदान किया गया स्ट्रीम जिसमें पूरा Excel वर्कबुक शामिल है।

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर श्रृंखला और श्रेणियाँ अपडेट की जाएँगी। यदि डेटा रेंज में श्रृंखलाओं की संख्या चार्ट डेटा में श्रृंखलाओं की गिनती से अधिक है तो वर्तमान संग्रह की अंतिम श्रृंखला के समान प्रकार की अतिरिक्त श्रृंखलाएँ संग्रह के अंत में जोड़ी जाएँगी।

**पैरामीटर** | **टाइप** | **विवरण**
--- | --- | ---
formula | java.lang.String | सेल्स डेटा रेंज सूत्र। उदाहरण: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"।

### getRange() {#getRange--}
```
public abstract String getRange()
```

चार्ट डेटा रेंज को प्राप्त करता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**रिटर्न:**
java.lang.String - सेल्स डेटा रेंज सूत्र। उदाहरण: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

चार्ट के डेटा स्रोत का प्रतिनिधित्व करता है।

**रिटर्न:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

यदि डेटा स्रोत बाहरी है तो बाहरी वर्कबुक पथ का प्रतिनिधित्व करता है, अन्यथा null।

**रिटर्न:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

समाहित वर्कबुक के प्रकार को प्राप्त करता है। यदि DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) है तो [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) लौटाता है। केवल पढ़ने योग्य [WorkbookType](../../com.aspose.slides/workbooktype)।

**रिटर्न:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

डेटा को अक्ष के ऊपर अदला-बदली करता है। X अक्ष पर चार्ट किया गया डेटा Y अक्ष पर स्थानांतरित हो जाएगा और इसके विपरीत।

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर** | **टाइप** | **विवरण**
--- | --- | ---
workbookPath | java.lang.String | लक्ष्य वर्कबुक का पथ

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर** | **टाइप** | **विवरण**
--- | --- | ---
workbookPath | java.lang.String | लक्ष्य वर्कबुक का पथ
updateChartData | boolean | यदि मान false है तो केवल वर्कबुक पथ अपडेट किया जाएगा। चार्ट डेटा लक्ष्य वर्कबुक से लोड नहीं होगा और अपडेट नहीं होगा। इसका उपयोग तब किया जा सकता है जब लक्ष्य वर्कबुक मौजूद न हो या उपलब्ध न हो। यदि मान true है तो चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा।