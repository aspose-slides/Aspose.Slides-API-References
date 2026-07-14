---
title: ChartData
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: चार्ट प्लॉटिंग के लिए उपयोग किए गए डेटा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartdata/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)  
```
public class ChartData extends DomObject<Chart> implements IChartData
```

चार्ट प्लॉटिंग के लिए उपयोग किए गए डेटा का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | चार्ट श्रृंखला या श्रेणियों के लिए उपयोग किए जाने वाले सेल्स बनाने हेतु सेल्स फैक्ट्री प्राप्त करता है। |
| [getSeries()](#getSeries--) | श्रृंखला प्राप्त करता है। |
| [getSeriesGroups()](#getSeriesGroups--) | श्रृंखला के समूह प्राप्त करता है। |
| [getCategories()](#getCategories--) | प्राथमिक श्रेणियाँ प्राप्त करता है (या यदि #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी false है तो प्राथमिक और द्वितीयक दोनों श्रेणियाँ)। |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | यदि false है तो #getSecondaryCategories.getSecondaryCategories प्रॉपर्टी null लौटाती है और #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग होता है। |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | यदि false है तो #getSecondaryCategories.getSecondaryCategories प्रॉपर्टी null लौटाती है और #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग होता है। |
| [getSecondaryCategories()](#getSecondaryCategories--) | यदि #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी true है तो द्वितीयक श्रेणियाँ प्राप्त करता है। |
| [readWorkbookStream()](#readWorkbookStream--) | इंटर्नली समाहित एक्सेल वर्कबुक को मेमोरी में एक स्ट्रीम में लिखता है। |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | उपयोगकर्ता-निर्दिष्ट मान के साथ इंटर्नली समाहित एक्सेल वर्कबुक को प्रारंभ करता है। |
| [getDataSourceType()](#getDataSourceType--) | यदि बाह्य डेटा स्रोत है तो बाहरी वर्कबुक पथ का प्रतिनिधित्व करता है, अन्यथा null। |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | चार्ट के डेटा स्रोत का प्रतिनिधित्व करता है। |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | एम्बेडेड वर्कबुक का प्रकार प्राप्त करता है। |
| [getRange()](#getRange--) | चार्ट डेटा रेंज प्राप्त करता है। |
| [setRange(String formula)](#setRange-java.lang.String-) | चार्ट डेटा रेंज सेट करता है। |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | बाहरी वर्कबुक को चार्ट के लिए डेटा स्रोत के रूप में सेट करता है। |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | बाहरी वर्कबुक को चार्ट के लिए डेटा स्रोत के रूप में सेट करता है। |
| [switchRowColumn()](#switchRowColumn--) | डेटा को अक्ष के ऊपर बदलता है। |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

चार्ट श्रृंखला या श्रेणियों के लिए उपयोग किए जाने वाले सेल्स बनाने हेतु सेल्स फैक्ट्री प्राप्त करता है। केवल-पढ़ने योग्य [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)।

**वापसी:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

श्रृंखला प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)।

**वापसी:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

श्रृंखला के समूह प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)।

--------------------

1) प्रत्येक श्रृंखला समूह में संयोज्य प्रकारों वाली श्रृंखलाएँ होती हैं। संयोज्य श्रृंखला प्रकारों के समूह CombinableSeriesTypesGroup एनम द्वारा परिभाषित और वर्णित हैं। साथ ही प्रत्येक श्रृंखला समूह में ऐसा श्रृंखला होता है जो या तो प्राथमिक अक्ष पर या द्वितीयक अक्ष पर प्लॉट किया जाता है (एक ही समूह में दोनों मामलों नहीं)। इसलिए, श्रृंखला समूहबद्ध करने का सिद्धांत उपरोक्त उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा समूहबद्ध करना है।

**वापसी:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

प्राथमिक श्रेणियाँ प्राप्त करता है (या यदि #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी false है तो प्राथमिक और द्वितीयक दोनों श्रेणियाँ)। केवल-पढ़ने योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

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

यदि #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी false है तो (#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और इस #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग होता है। यदि #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी true है तो (#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग होता है और इस #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है।

**वापसी:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

यदि false है तो #getSecondaryCategories.getSecondaryCategories प्रॉपर्टी null लौटाती है और #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग होता है। यदि true है तो #getSecondaryCategories.getSecondaryCategories प्रॉपर्टी में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग होता है और #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है। पढ़ने/लिखने योग्य बूलियन।

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
public final void setUseSecondaryCategories(boolean value)
```

यदि false है तो #getSecondaryCategories.getSecondaryCategories प्रॉपर्टी null लौटाती है और #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग होता है। यदि true है तो #getSecondaryCategories.getSecondaryCategories प्रॉपर्टी में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग होता है और #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है। पढ़ने/लिखने योग्य बूलियन।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

यदि #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी true है तो द्वितीयक श्रेणियाँ प्राप्त करता है। केवल-पढ़ने योग्य [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)।

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

यदि #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी false है तो यह (#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी null लौटाती है और #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग होता है। यदि #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) प्रॉपर्टी true है तो इस (#getSecondaryCategories.getSecondaryCategories) प्रॉपर्टी में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग होता है और #getCategories.getCategories प्रॉपर्टी में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग होता है।

**वापसी:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

इंटर्नली समाहित एक्सेल वर्कबुक को मेमोरी में एक स्ट्रीम में लिखता है।

**वापसी:**  
byte[] - इंटर्नली समाहित एक्सेल वर्कबुक की कॉपी वाली बाइट एरे का एक इंस्टेंस लौटाता है।

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

उपयोगकर्ता-निर्दिष्ट मान के साथ इंटर्नली समाहित एक्सेल वर्कबुक को प्रारंभ करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| ms | byte[] | उपयोगकर्ता द्वारा प्रदान किया गया स्ट्रीम जिसमें पूर्ण एक्सेल वर्कबुक होता है। |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

यदि बाह्य डेटा स्रोत है तो बाहरी वर्कबुक पथ का प्रतिनिधित्व करता है, अन्यथा null।

**वापसी:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

चार्ट के डेटा स्रोत का प्रतिनिधित्व करता है।

**वापसी:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

एम्बेडेड वर्कबुक का प्रकार प्राप्त करता है। यदि DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) है तो [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) लौटाता है। केवल-पढ़ने योग्य [WorkbookType](../../com.aspose.slides/workbooktype)।

**वापसी:**  
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

**वापसी:**  
java.lang.String - सेल्स डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर श्रृंखला और श्रेणियाँ अपडेट की जाएँगी। यदि डेटा रेंज में श्रृंखलाओं की संख्या चार्ट डेटा में श्रृंखलाओं की संख्या से अधिक है तो वर्तमान संग्रह में अंतिम श्रृंखला के समान प्रकार की अतिरिक्त श्रृंखलाएँ संग्रह के अंत में जोड़ी जाएँगी।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| formula | java.lang.String | सेल्स डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| workbookPath | java.lang.String | लक्ष्य वर्कबुक का पथ |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| workbookPath | java.lang.String | लक्ष्य वर्कबुक का पथ |
| updateChartData | boolean | यदि मान false है तो केवल वर्कबुक पथ अपडेट होगा। चार्ट डेटा लक्ष्य वर्कबुक से लोड और अपडेट नहीं होगा। इसका उपयोग तब किया जा सकता है जब लक्ष्य वर्कबुक मौजूद नहीं है या उपलब्ध नहीं है। यदि मान true है तो चार्ट डेटा लक्ष्य वर्कबुक से अपडेट होगा। |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

डेटा को अक्ष के ऊपर स्वैप करता है। X अक्ष पर चार्ट किया गया डेटा Y अक्ष पर चलेगा और इसके विपरीत।