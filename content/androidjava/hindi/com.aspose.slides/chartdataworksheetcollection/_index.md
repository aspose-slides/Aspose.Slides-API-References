---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: चार्ट डेटा वर्कबुक की कार्यपत्रकों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartdataworksheetcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

चार्ट डेटा वर्कबुक की कार्यपत्रकों के संग्रह का प्रतिनिधित्व करता है।

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
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा कार्यपत्रक लौटाता है। |
| [size()](#size--) | गिनती लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए java iterator लौटाता है। |
| [iterator()](#iterator--) | संग्रह पर इटेरेट करने वाला enumerator लौटाता है। |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट array में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाता है कि क्या संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सेफ़) है। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

इंडेक्स द्वारा कार्यपत्रक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में कार्यपत्रक का इंडेक्स। |

**वापसी:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet का उदाहरण।

### size() {#size--}
```
public final int size()
```

गिनती लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

पूरे संग्रह के लिए java iterator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - एक IGenericEnumerator जो संग्रह पर इटेरेट करने के लिए उपयोग किया जा सकता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

संग्रह पर इटेरेट करने वाला enumerator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - एक IGenericEnumerator जो संग्रह पर इटेरेट करने के लिए उपयोग किया जा सकता है।

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | कॉपी किए जाने वाला array। |
| arrayIndex | int | कॉपी शुरू करने का इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

यह दर्शाता है कि क्या संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सेफ़) है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**
java.lang.Object