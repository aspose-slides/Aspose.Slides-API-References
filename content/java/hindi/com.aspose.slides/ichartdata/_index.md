---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /hi/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

एक चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा को दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | चार्ट सीरीज़ या कैटेगरीज़ के लिए उपयोग किए जाने वाले सेल्स बनाने के लिए सेल्स फ़ैक्टरी प्राप्त करता है। |
| [getSeries()](#getSeries--) | सीरीज़ प्राप्त करता है। |
| [getSeriesGroups()](#getSeriesGroups--) | सीरीज़ के समूह प्राप्त करता है। |
| [getCategories()](#getCategories--) | प्राथमिक कैटेगरीज़ (या प्राथमिक एवं द्वितीयक कैटेगरीज़ दोनों यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रविष्टि false है) प्राप्त करता है। |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग किया जाता है। |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग किया जाता है। |
| [getSecondaryCategories()](#getSecondaryCategories--) | यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी true है तो द्वितीयक कैटेगरीज़ प्राप्त करता है। |
| [readWorkbookStream()](#readWorkbookStream--) | आंतरिक रूप से सम्मिलित Excel वर्कबुक को इन-मे़मोरी स्ट्रीम में लिखता है। |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | उपयोगकर्ता-निर्दिष्ट मान के साथ आंतरिक रूप से सम्मिलित Excel वर्कबुक को प्रारंभ करता है। |
| [setRange(String formula)](#setRange-java.lang.String-) | चार्ट डेटा रेंज सेट करता है। |
| [getRange()](#getRange--) | चार्ट डेटा रेंज प्राप्त करता है। |
| [getDataSourceType()](#getDataSourceType--) | चार्ट का डेटा स्रोत दर्शाता है |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | यदि डेटा स्रोत बाहरी है तो बाहरी वर्कबुक पाथ दर्शाता है, अन्यथा null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | एम्बेडेड वर्कबुक का प्रकार प्राप्त करता है। |
| [switchRowColumn()](#switchRowColumn--) | अक्षों के पार डेटा को स्वैप करता है। |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। |
| [refreshData()](#refreshData--) | स्रोत वर्कबुक से पुनः लोड करके चार्ट डेटा को रिफ्रेश करता है। |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


चार्ट सीरीज़ या कैटेगरीज़ के लिए उपयोग किए जाने वाले सेल्स बनाने के लिए सेल्स फ़ैक्टरी प्राप्त करता है। केवल-पढ़ने योग्य [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)।

**रिटर्न:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


सीरीज़ प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)।

**रिटर्न:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


सीरीज़ के समूह प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)।

--------------------

1) प्रत्येक सीरीज़ समूह में संयोज्य प्रकार की सीरीज़ होती है। संयोज्य सीरीज़ प्रकारों को CombinableSeriesTypesGroup एनोम के साथ परिभाषित व वर्णित किया गया है। साथ ही प्रत्येक समूह में ऐसी सीरीज़ होती है जो प्राथमिक अक्ष या द्वितीयक अक्ष पर प्लॉट की जाती है (एक ही समूह में दोनों नहीं)। इसलिए, सीरीज़ ग्रुपिंग का सिद्धांत ऊपर उल्लेखित प्रकार समूह और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा किया जाता है। 2) सीरीज़ समूह में कुछ सीरीज़ गुण होते हैं जो समूह की प्रत्येक सीरीज़ के लिए समान होते हैं ("सीरीज़ समूह गुण")। ChartSeriesGroup क्लास में "सीरीज़ समूह गुण" पढ़ने/लिखने योग्य हैं। प्रत्येक "सीरीज़ समूह गुण" का ChartSeries क्लास में केवल-पढ़ने योग्य प्रोजेक्शन हो सकता है।

**रिटर्न:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


प्राथमिक कैटेगरीज़ (या प्राथमिक एवं द्वितीयक कैटेगरीज़ दोनों यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी false है) प्राप्त करता है। केवल-पढ़ने योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियां हैं series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियां हैं series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और इस (\#getCategories.getCategories) प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग किया जाता है। यदि यह प्रॉपर्टी true है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक सीरीज़ के लिए उपयोग किया जाता है और इस (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है।

**रिटर्न:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग किया जाता है। यदि true है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक सीरीज़ के लिए उपयोग किया जाता है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य बूलियन।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियां हैं series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियां हैं series.getChart().getChartData().getCategories()
>  }
> ```

**रिटर्न:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग किया जाता है। यदि true है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक सीरीज़ के लिए उपयोग किया जाता है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य बूलियन।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियां हैं series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियां हैं series.getChart().getChartData().getCategories()
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```


यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी true है तो द्वितीयक कैटेगरीज़ प्राप्त करता है। केवल-पढ़ने योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियां हैं series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियां हैं series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी false है तो यह (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग किया जाता है। यदि यह प्रॉपर्टी true है तो इस (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक सीरीज़ के लिए उपयोग किया जाता है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है।

**रिटर्न:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


आंतरिक रूप से सम्मिलित Excel वर्कबुक को इन-मे़मोरी स्ट्रीम में लिखता है।

**रिटर्न:**
byte[] - आंतरिक रूप से सम्मिलित Excel वर्कबुक की प्रतिलिपि युक्त बाइट ऐरे लौटाता है।
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


उपयोगकर्ता-निर्दिष्ट मान के साथ आंतरिक रूप से सम्मिलित Excel वर्कबुक को प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ms | byte[] | उपयोगकर्ता द्वारा प्रदान किया गया स्ट्रिम जिसमें संपूर्ण Excel वर्कबुक सम्मिलित है। |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर सीरीज़ और कैटेगरीज़ अपडेट किए जाएंगे। यदि डेटा रेंज में सीरीज़ की संख्या चार्ट डेटा में मौजूद सीरीज़ की संख्या से अधिक है तो वर्तमान कलेक्शन में अंतिम सीरीज़ के समान प्रकार की अतिरिक्त सीरीज़ कलेक्शन के अंत में जोड़ दी जाएँगी।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | सेल्स डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```


चार्ट डेटा रेंज प्राप्त करता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**रिटर्न:**
java.lang.String - सेल्स डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


चार्ट का डेटा स्रोत दर्शाता है

**रिटर्न:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


यदि डेटा स्रोत बाहरी है तो बाहरी वर्कबुक पाथ दर्शाता है, अन्यथा null

**रिटर्न:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


एम्बेडेड वर्कबुक का प्रकार प्राप्त करता है। यदि DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) है तो [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) लौटाता है। केवल-पढ़ने योग्य [WorkbookType](../../com.aspose.slides/workbooktype)।

**रिटर्न:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


अक्षों के पार डेटा को स्वैप करता है। X-अक्स पर चार्ट किया गया डेटा Y-अक्स पर और इसके विपरीत चलेगा।

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। लक्ष्य वर्कबुक से चार्ट डेटा अपडेट किया जाएगा।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| workbookPath | java.lang.String | लक्ष्य वर्कबुक का पाथ |

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| workbookPath | java.lang.String | लक्ष्य वर्कबुक का पाथ |
| updateChartData | boolean | यदि मान false है तो केवल वर्कबुक पाथ अपडेट होगा। चार्ट डेटा लक्ष्य वर्कबुक से लोड या अपडेट नहीं होगा। इसे तब उपयोग किया जा सकता है जब लक्ष्य वर्कबुक मौजूद न हो या उपलब्ध न हो। यदि मान true है तो चार्ट डेटा लक्ष्य वर्कबुक से अपडेट होगा। |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```


स्रोत वर्कबुक से पुनः लोड करके चार्ट डेटा को रिफ्रेश करता है।

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```