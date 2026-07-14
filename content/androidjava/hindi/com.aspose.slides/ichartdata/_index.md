---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /hi/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

एक चार्ट प्लॉटिंग के लिए उपयोग किए गए डेटा का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किए जाने वाले सेल बनाने के लिए सेल फ़ैक्ट्री प्राप्त करता है। |
| [getSeries()](#getSeries--) | सीरीज़ प्राप्त करता है। |
| [getSeriesGroups()](#getSeriesGroups--) | सीरीज़ के समूह प्राप्त करता है। |
| [getCategories()](#getCategories--) | प्राथमिक श्रेणियों को प्राप्त करता है (या यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी false है तो प्राथमिक और द्वितीयक दोनों श्रेणियाँ)। |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है। |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है। |
| [getSecondaryCategories()](#getSecondaryCategories--) | यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी true है तो द्वितीयक श्रेणियों को प्राप्त करता है। |
| [readWorkbookStream()](#readWorkbookStream--) | इंटर्नली सम्मिलित Excel वर्कबुक को इन-मेमोरी स्ट्रीम में लिखता है। |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | उपयोगकर्ता-निर्दिष्ट मान के साथ इंटर्नली सम्मिलित Excel वर्कबुक को प्रारंभ करता है। |
| [setRange(String formula)](#setRange-java.lang.String-) | चार्ट डेटा रेंज सेट करता है। |
| [getRange()](#getRange--) | चार्ट डेटा रेंज प्राप्त करता है। |
| [getDataSourceType()](#getDataSourceType--) | चार्ट का डेटा स्रोत दर्शाता है। |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | यदि डेटा स्रोत बाहरी है तो बाहरी वर्कबुक पाथ दर्शाता है, अन्यथा null। |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | एंबेडेड वर्कबुक के प्रकार को प्राप्त करता है। |
| [switchRowColumn()](#switchRowColumn--) | धुरी पर डेटा को अदला-बदली करता है। |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | चार्ट के डेटा स्रोत के रूप में बाहरी वर्कबुक सेट करता है। |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | चार्ट के डेटा स्रोत के रूप में बाहरी वर्कबुक सेट करता है। |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किए जाने वाले सेल बनाने के लिए सेल फ़ैक्ट्री प्राप्त करता है। केवल-पढ़ें [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**वापसी:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

सीरीज़ प्राप्त करता है। केवल-पढ़ें [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**वापसी:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

सीरीज़ के समूह प्राप्त करता है। केवल-पढ़ें [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) प्रत्येक सीरीज़ समूह में संयोज्य प्रकारों वाली सीरीज़ होती हैं। संयोज्य सीरीज़ प्रकारों के समूह CombinableSeriesTypesGroup enum द्वारा परिभाषित और वर्णित हैं। साथ ही प्रत्येक सीरीज़ समूह में ऐसी सीरीज़ शामिल होती हैं जो प्राथमिक अक्ष पर या द्वितीयक अक्ष पर प्लॉट की जाती हैं (एक ही समूह में दोनों मामलों नहीं)। इसलिए, सीरीज़ समूह बनाने का सिद्धांत उपर्युक्त प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा वर्गीकरण है। 2) सीरीज़ समूह में कुछ सीरीज़ गुण होते हैं जो समूह की प्रत्येक सीरीज़ के लिए सामान्य होते हैं ("series group properties")। ChartSeriesGroup क्लास में "series group properties" पढ़ें/लिखें हैं। प्रत्येक "series group properties" का ChartSeries क्लास में केवल-पढ़ें प्रोजेक्शन हो सकता है।

**वापसी:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

प्राथमिक श्रेणियों को प्राप्त करता है (या यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी false है तो प्राथमिक और द्वितीयक दोनों श्रेणियाँ)। केवल-पढ़ें [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और इस (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है। यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी true है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक सीरीज़ के लिए और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है।

**वापसी:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है। यदि true है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक सीरीज़ के लिए और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है। पढ़ें/लिखें बूलियन।

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


**वापसी:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

यदि false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है। यदि true है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक सीरीज़ के लिए और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है। पढ़ें/लिखें बूलियन।

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


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी true है तो द्वितीयक श्रेणियों को प्राप्त करता है। केवल-पढ़ें [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी false है तो यह (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और (\#getCategories.getCategories) प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है। यदि (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) प्रॉपर्टी true है तो यह (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी डेटा द्वितीयक सीरीज़ के लिए और (\#getCategories.getCategories) प्रॉपर्टी डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है।

**वापसी:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

इंटर्नली सम्मिलित Excel वर्कबुक को इन-मेमोरी स्ट्रीम में लिखता है।

**वापसी:**
byte[] - इंटर्नली सम्मिलित Excel वर्कबुक की एक प्रति समाहित करने वाले बाइट्स की सरणी लौटाता है।

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

उपयोगकर्ता-निर्दिष्ट मान के साथ इंटर्नली सम्मिलित Excel वर्कबुक को प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ms | byte[] | पूरे Excel वर्कबुक को समाहित करने वाला उपयोगकर्ता-प्रदान किया गया स्ट्रीम। |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर सीरीज़ और श्रेणियों को अपडेट किया जाएगा। यदि डेटा रेंज में सीरीज़ की संख्या चार्ट डेटा में सीरीज़ की संख्या से अधिक है तो वर्तमान संग्रह की अंतिम सीरीज़ के समान प्रकार की अतिरिक्त सीरीज़ संग्रह के अंत में जोड़ी जाएगी।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | सेल डेटा रेंज सूत्र। उदाहरण: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

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

**वापसी:**
java.lang.String - सेल डेटा रेंज सूत्र। उदाहरण: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

चार्ट का डेटा स्रोत दर्शाता है।

**वापसी:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

यदि डेटा स्रोत बाहरी है तो बाहरी वर्कबुक पथ दर्शाता है, अन्यथा null।

**वापसी:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

एंबेडेड वर्कबुक के प्रकार को प्राप्त करता है। यदि DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) है तो [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) लौटाता है। केवल-पढ़ें [WorkbookType](../../com.aspose.slides/workbooktype)।

**वापसी:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

धुरी पर डेटा को अदला-बदली करता है। X अक्ष पर चार्ट किया गया डेटा Y अक्ष पर चलेगा और इसके विपरीत।

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

चार्ट के डेटा स्रोत के रूप में बाहरी वर्कबुक सेट करता है। लक्ष्य वर्कबुक से चार्ट डेटा अपडेट किया जाएगा।

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
| workbookPath | java.lang.String | लक्ष्य वर्कबुक का पथ |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

चार्ट के डेटा स्रोत के रूप में बाहरी वर्कबुक सेट करता है।

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
| workbookPath | java.lang.String | लक्ष्य वर्कबुक का पथ |
| updateChartData | boolean | यदि मान false है तो केवल वर्कबुक पाथ अपडेट होगा। चार्ट डेटा लक्ष्य वर्कबुक से लोड या अपडेट नहीं होगा। इसे तब उपयोग किया जा सकता है जब लक्ष्य वर्कबुक मौजूद नहीं है या उपलब्ध नहीं है। यदि मान true है तो चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा। |