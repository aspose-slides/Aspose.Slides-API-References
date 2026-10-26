---
title: ChartData
second_title: Aspose.Slides for Java API संदर्भ
description: चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/chartdata/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)  
```
public class ChartData extends DomObject<Chart> implements IChartData
```

चार्ट प्लॉटिंग के लिए उपयोग किया गया डेटा दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किए जाने वाले सेल्स बनाने के लिए सेल्स फैक्ट्री प्राप्त करता है। |
| [getSeries()](#getSeries--) | सीरीज प्राप्त करता है। |
| [getSeriesGroups()](#getSeriesGroups--) | सीरीज़ के समूह प्राप्त करता है। |
| [getCategories()](#getCategories--) | प्राथमिक श्रेणियां प्राप्त करता है (या यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी false है तो दोनों प्राथमिक और द्वितीयक श्रेणियां)। |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | यदि false है तो \#getSecondaryCategories.getSecondaryCategories प्रॉपर्टी null लौटाएगी और \#getCategories.getCategories प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग होगा। |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | यदि false है तो \#getSecondaryCategories.getSecondaryCategories प्रॉपर्टी null लौटाएगी और \#getCategories.getCategories प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग होगा। |
| [getSecondaryCategories()](#getSecondaryCategories--) | यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी true है तो द्वितीयक श्रेणियां प्राप्त करता है। |
| [readWorkbookStream()](#readWorkbookStream--) | आंतरिक रूप से सम्मिलित Excel वर्कबुक को मेमोरी स्ट्रीम में लिखता है। |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | उपयोगकर्ता द्वारा निर्दिष्ट मान के साथ आंतरिक रूप से सम्मिलित Excel वर्कबुक को प्रारंभ करता है। |
| [getDataSourceType()](#getDataSourceType--) | यदि बाहरी डेटा स्रोत है तो बाहरी वर्कबुक पाथ दर्शाता है, अन्यथा null। |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | चार्ट के डेटा स्रोत को दर्शाता है। |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | एम्बेडेड वर्कबुक के प्रकार को प्राप्त करता है। |
| [getRange()](#getRange--) | चार्ट डेटा रेंज प्राप्त करता है। |
| [setRange(String formula)](#setRange-java.lang.String-) | चार्ट डेटा रेंज सेट करता है। |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | चार्ट के डेटा स्रोत के रूप में बाहरी वर्कबुक सेट करता है। |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | चार्ट के डेटा स्रोत के रूप में बाहरी वर्कबुक सेट करता है। |
| [switchRowColumn()](#switchRowColumn--) | अक्ष के ऊपर डेटा को स्वैप करता है। |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किए जाने वाले सेल्स बनाने के लिए सेल्स फैक्ट्री प्राप्त करता है। केवल-पढ़ने योग्य [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)।

**रिटर्न:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

सीरीज प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)।

**रिटर्न:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

सीरीज़ के समूह प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)।

1) प्रत्येक समूह में संयोज्य प्रकारों की सीरीज़ शामिल होती हैं। संयोज्य सीरीज़ प्रकारों के समूह `CombinableSeriesTypesGroup` एन्हम द्वारा परिभाषित और वर्णित होते हैं। प्रत्येक समूह में ऐसी सीरीज़ भी होती हैं जो या तो प्राथमिक अक्ष पर या द्वितीयक अक्ष पर प्लॉट की जाती हैं (एक ही समूह में दोनों नहीं)। इसलिए, समूहकरण का सिद्धांत ऊपर उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा होता है। 2) समूह में कुछ सीरीज़ प्रॉपर्टीज़ होती हैं जो समूह की प्रत्येक सीरीज़ के लिए सामान्य होती हैं ("सीरीज़ समूह प्रॉपर्टीज़")। `ChartSeriesGroup` क्लास में ये प्रॉपर्टीज़ पढ़ें/लिखें योग्य हैं। प्रत्येक "सीरीज़ समूह प्रॉपर्टी" का केवल-पढ़ने योग्य प्रोजेक्शन `ChartSeries` क्लास में हो सकता है।

**रिटर्न:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

प्राथमिक श्रेणियां प्राप्त करता है (या यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी false है तो दोनों प्राथमिक और द्वितीयक श्रेणियां)। केवल-पढ़ने योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

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

यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी false है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और इस \#getCategories.getCategories प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग होगा। यदि प्रॉपर्टी true है तो (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी का डेटा द्वितीयक सीरीज़ के लिए और इस \#getCategories.getCategories प्रॉपर्टी का डेटा प्राथमिक सीरीज़ के लिए उपयोग होगा।

**रिटर्न:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

यदि false है तो \#getSecondaryCategories.getSecondaryCategories प्रॉपर्टी null लौटाती है और \#getCategories.getCategories प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग होगा। यदि true है तो \#getSecondaryCategories.getSecondaryCategories प्रॉपर्टी का डेटा द्वितीयक सीरीज़ के लिए और \#getCategories.getCategories प्रॉपर्टी का डेटा प्राथमिक सीरीज़ के लिए उपयोग होगा। पढ़ें/लिखें boolean।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियां series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियां series.getChart().getChartData().getCategories()
>  }
> ```


**रिटर्न:**  
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

यदि false है तो \#getSecondaryCategories.getSecondaryCategories प्रॉपर्टी null लौटाती है और \#getCategories.getCategories प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग होगा। यदि true है तो \#getSecondaryCategories.getSecondaryCategories प्रॉपर्टी का डेटा द्वितीयक सीरीज़ के लिए और \#getCategories.getCategories प्रॉपर्टी का डेटा प्राथमिक सीरीज़ के लिए उपयोग होगा। पढ़ें/लिखें boolean।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियां series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियां series.getChart().getChartData().getCategories()
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

द्वितीयक श्रेणियां प्राप्त करता है यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी true है। केवल-पढ़ने योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // संबंधित श्रेणियां series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // संबंधित श्रेणियां series.getChart().getChartData().getCategories()
>  }
> ```


यदि \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी false है तो यह (\#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और \#getCategories.getCategories प्रॉपर्टी में डेटा दोनों प्राथमिक और द्वितीयक सीरीज़ के लिए उपयोग होगा। यदि प्रॉपर्टी true है तो इस \#getSecondaryCategories.getSecondaryCategories प्रॉपर्टी का डेटा द्वितीयक सीरीज़ के लिए और \#getCategories.getCategories प्रॉपर्टी का डेटा प्राथमिक सीरीज़ के लिए उपयोग होगा।

**रिटर्न:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

आंतरिक रूप से सम्मिलित Excel वर्कबुक को मेमोरी में स्ट्रीम के रूप में लिखता है।

**रिटर्न:**  
byte[] - एक बाइट एरे की इंस्टेंस लौटाता है जिसमें आंतरिक रूप से सम्मिलित Excel वर्कबुक की कॉपी होती है।

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

आंतरिक रूप से सम्मिलित Excel वर्कबुक को उपयोगकर्ता द्वारा निर्दिष्ट मान के साथ प्रारंभ करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ms | byte[] | उपयोगकर्ता-प्रदान किया गया स्ट्रीम जिसमें पूरा Excel वर्कबुक हो। |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

यदि बाहरी डेटा स्रोत है तो बाहरी वर्कबुक पाथ दर्शाता है, अन्यथा null।

**रिटर्न:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

चार्ट के डेटा स्रोत को दर्शाता है।

**रिटर्न:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

एम्बेडेड वर्कबुक के प्रकार को प्राप्त करता है। यदि DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) है तो [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) लौटाता है। केवल-पढ़ने योग्य [WorkbookType](../../com.aspose.slides/workbooktype)।

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
>   finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**रिटर्न:**  
java.lang.String - Cells डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर सीरीज़ और श्रेणियां अपडेट की जाएँगी। यदि डेटा रेंज में सीरीज़ की संख्या चार्ट डेटा में सीरीज़ की संख्या से अधिक है तो वर्तमान संग्रह में अंतिम सीरीज़ के समान प्रकार की अतिरिक्त सीरीज़ संग्रह के अंत में जोड़ी जाएगी।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | सेल्स डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

चार्ट के डेटा स्रोत के रूप में बाहरी वर्कबुक सेट करता है। चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| workbookPath | java.lang.String | लक्ष्य वर्कबुक का पाथ |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

चार्ट के डेटा स्रोत के रूप में बाहरी वर्कबुक सेट करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| workbookPath | java.lang.String | लक्ष्य वर्कबुक का पाथ |
| updateChartData | boolean | यदि मान false है तो केवल वर्कबुक पाथ अपडेट होगा। चार्ट डेटा लक्ष्य वर्कबुक से लोड या अपडेट नहीं होगा। इसका उपयोग तब किया जा सकता है जब लक्ष्य वर्कबुक मौजूद न हो या उपलब्ध न हो। यदि मान true है तो चार्ट डेटा लक्ष्य वर्कबुक से अपडेट होगा। |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

डेटा को अक्ष के ऊपर स्वैप करें। X अक्ष पर चार्ट किया गया डेटा Y अक्ष पर चलेगा और इसके विपरीत।