---
title: ChartData
second_title: Aspose.Slides for Java API संदर्भ
description: एक चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartdata/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)  
```
public class ChartData extends DomObject<Chart> implements IChartData
```

चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा का प्रतिनिधित्व करता है।

## Methods

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | चार्ट श्रृंखला या श्रेणियों के लिए उपयोग किए जाने वाले सेल बनाने के लिए सेल फैक्ट्री प्राप्त करता है। |
| [getSeries()](#getSeries--) | श्रृंखलाएँ प्राप्त करता है। |
| [getSeriesGroups()](#getSeriesGroups--) | श्रृंखलाओं के समूह प्राप्त करता है। |
| [getCategories()](#getCategories--) | प्राथमिक श्रेणियाँ (या यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) गुण false है तो दोनों प्राथमिक और द्वितीयक श्रेणियाँ) प्राप्त करता है। |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | यदि false है तो \#getSecondaryCategories.getSecondaryCategories गुण null लौटाता है और \#getCategories.getCategories गुण में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है। |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | यदि false है तो \#getSecondaryCategories.getSecondaryCategories गुण null लौटाता है और \#getCategories.getCategories गुण में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है। |
| [getSecondaryCategories()](#getSecondaryCategories--) | यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) गुण true है तो द्वितीयक श्रेणियाँ प्राप्त करता है। |
| [readWorkbookStream()](#readWorkbookStream--) | आंतरिक रूप से समाहित Excel वर्कबुक को इन-मे्मोरी स्ट्रीम में लिखता है। |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | उपयोगकर्ता-निर्दिष्ट मान के साथ आंतरिक रूप से समाहित Excel वर्कबुक को प्रारम्भ करता है। |
| [getDataSourceType()](#getDataSourceType--) | यदि बाहरी डेटा स्रोत है तो बाहरी वर्कबुक पथ का प्रतिनिधित्व करता है, अन्यथा null। |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | चार्ट का डेटा स्रोत प्रतिनिधित्व करता है। |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | एंबेडेड वर्कबुक का प्रकार प्राप्त करता है। |
| [getRange()](#getRange--) | चार्ट डेटा रेंज प्राप्त करता है। |
| [setRange(String formula)](#setRange-java.lang.String-) | चार्ट डेटा रेंज सेट करता है। |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। |
| [refreshData()](#refreshData--) | स्रोत वर्कबुक से पुनः लोड करके चार्ट डेटा को रीफ़्रेश करता है। |
| [switchRowColumn()](#switchRowColumn--) | धुरी के ऊपर डेटा को बदलें। |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

चार्ट श्रृंखला या श्रेणियों के लिए उपयोग किए जाने वाले सेल बनाने के लिए सेल फैक्ट्री प्राप्त करता है। केवल-पढ़ने-योग्य [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**रिटर्न:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

श्रृंखलाएँ प्राप्त करता है। केवल-पढ़ने-योग्य [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**रिटर्न:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

श्रृंखला समूह प्राप्त करता है। केवल-पढ़ने-योग्य [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) प्रत्येक श्रृंखला समूह में संयोज्य प्रकारों वाली श्रृंखलाएँ होती हैं। संयोज्य श्रृंखला प्रकारों के समूह CombinableSeriesTypesGroup enum द्वारा परिभाषित और वर्णित हैं। साथ ही प्रत्येक श्रृंखला समूह में ऐसी श्रृंखलाएँ होती हैं जो या तो प्राथमिक अक्ष पर या द्वितीयक अक्ष पर प्लॉट की जाती हैं (एक ही समूह में दोनों नहीं)। अतः श्रृंखला समूहबद्धता का सिद्धान्त ऊपर उल्लिखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा किया जाता है। 2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह के प्रत्येक श्रृंखला के लिए सामान्य होते हैं (“series group properties”)। ChartSeriesGroup क्लास में “series group properties” पढ़ने-लिखने-योग्य हैं। प्रत्येक “series group property” का एक केवल-पढ़ने-योग्य प्रोजेक्शन ChartSeries क्लास में हो सकता है।

**रिटर्न:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

प्राथमिक श्रेणियाँ (या यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) गुण false है तो दोनों प्राथमिक और द्वितीयक श्रेणियाँ) प्राप्त करता है। केवल-पढ़ने-योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getSecondaryCategories() हैं
>  }
>  else
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getCategories() हैं
>  }
> ```

--------------------

यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) गुण false है तो (\#getSecondaryCategories.getSecondaryCategories) गुण null लौटाता है और इस \#getCategories.getCategories गुण में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है। यदि यह गुण true है तो (\#getSecondaryCategories.getSecondaryCategories) गुण द्वितीयक श्रृंखलाओं के लिए उपयोग होता है और इस \#getCategories.getCategories गुण का डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है।

**रिटर्न:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

यदि false है तो \#getSecondaryCategories.getSecondaryCategories गुण null लौटाता है और \#getCategories.getCategories गुण में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है। यदि true है तो \#getSecondaryCategories.getSecondaryCategories गुण का डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग होता है और \#getCategories.getCategories गुण का डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है। पढ़ने/लिखने-योग्य boolean।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getSecondaryCategories() हैं
>  }
>  else
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getCategories() हैं
>  }
> ```

**रिटर्न:**  
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

यदि false है तो \#getSecondaryCategories.getSecondaryCategories गुण null लौटाता है और \#getCategories.getCategories गुण में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है। यदि true है तो \#getSecondaryCategories.getSecondaryCategories गुण का डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग होता है और \#getCategories.getCategories गुण का डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है। पढ़ने/लिखने-योग्य boolean।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getSecondaryCategories() हैं
>  }
>  else
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getCategories() हैं
>  }
> ```

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) गुण true है तो द्वितीयक श्रेणियाँ प्राप्त करता है। केवल-पढ़ने-योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getSecondaryCategories() हैं
>  }
>  else
>  {
>      // संबंधित श्रेणियाँ series.getChart().getChartData().getCategories() हैं
>  }
> ```

--------------------

यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) गुण false है तो यह (\#getSecondaryCategories.getSecondaryCategories) गुण null लौटाता है और \#getCategories.getCategories गुण में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है। यदि यह गुण true है तो इस \#getSecondaryCategories.getSecondaryCategories गुण का डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग होता है और \#getCategories.getCategories गुण का डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है।

**रिटर्न:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

आंतरिक रूप से समाहित Excel वर्कबुक को इन-मे्मोरी स्ट्रीम में लिखता है।

**रिटर्न:**  
byte[] - आंतरिक रूप से समाहित Excel वर्कबुक की प्रति संग्रहीत बाइट ऐरे का एक उदाहरण लौटाता है।

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

आंतरिक रूप से समाहित Excel वर्कबुक को उपयोगकर्ता-निर्दिष्ट मान के साथ प्रारम्भ करता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | उपयोगकर्ता-द्वारा प्रदान किया गया स्ट्रीम जिसमें पूरी Excel वर्कबुक सम्मिलित है। |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

यदि बाहरी डेटा स्रोत है तो बाहरी वर्कबुक पथ का प्रतिनिधित्व करता है, अन्यथा null।

**रिटर्न:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

चार्ट का डेटा स्रोत प्रतिनिधित्व करता है।

**रिटर्न:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

एंबेडेड वर्कबुक का प्रकार प्राप्त करता है। यदि DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) है तो [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) लौटाता है। केवल-पढ़ने-योग्य [WorkbookType](../../com.aspose.slides/workbooktype)।

**रिटर्न:**  
int

### getRange() {#getRange--}
```
public final String getRange()
```

चार्ट डेटा रेंज प्राप्त करता है।

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**रिटर्न:**  
java.lang.String - सेल डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर श्रृंखला और श्रेणियाँ अपडेट की जाएँगी। यदि डेटा रेंज में श्रृंखलाओं की संख्या चार्ट डेटा में श्रृंखलाओं की गिनती से अधिक है तो वर्तमान संग्रह में अंतिम श्रृंखला के समान प्रकार की अतिरिक्त श्रृंखलाएँ संग्रह के अंत में जोड़ी जाएँगी।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | सेल डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। लक्षित वर्कबुक से चार्ट डेटा अपडेट होगा।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | लक्षित वर्कबुक का पथ |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | लक्षित वर्कबुक का पथ |
| updateChartData | boolean | यदि मान false है तो केवल वर्कबुक पथ अपडेट होगा। चार्ट डेटा लक्षित वर्कबुक से लोड और अपडेट नहीं होगा। यह तब उपयोग किया जा सकता है जब लक्षित वर्कबुक मौजूद नहीं है या उपलब्ध नहीं है। यदि मान true है तो चार्ट डेटा लक्षित वर्कबुक से अपडेट होगा। |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

स्रोत वर्कबुक से पुनः लोड करके चार्ट डेटा को रीफ़्रेश करता है।

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

धुरी के ऊपर डेटा को बदलें। X-अक्ष पर चार्ट किए गया डेटा Y-अक्ष पर चलेगा और इसके विपरीत।