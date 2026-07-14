---
title: ChartSeriesCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: संग्रह का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/chartseriescollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

संग्रह का प्रतिनिधित्व करता है [ChartSeries](../../com.aspose.slides/chartseries)
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [size()](#size--) | संग्रह में वस्तुओं की संख्या लौटाता है। |
| [add(int type)](#add-int-) | नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [insert(int index, int type)](#insert-int-int-) | नया चार्ट सीरीज़ बनाता है और इसे संग्रह में सम्मिलित करता है। |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | [ChartDataCell](../../com.aspose.slides/chartdatacell) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | [ChartCellCollection](../../com.aspose.slides/chartcellcollection) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [add(String name, int type)](#add-java.lang.String-int-) | मान से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | निर्दिष्ट [ChartSeries](../../com.aspose.slides/chartseries) को खोजता है और संपूर्ण Collection के भीतर प्रथम प्रकट होने का शून्य-आधारित सूचकांक लौटाता है |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह से निर्दिष्ट स्थिति पर संग्रहीत ActiveX नियंत्रण को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी नियंत्रणों को हटाता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह के माध्यम से पुनरावृत करता है। |
| [iteratorJava()](#iteratorJava--) | संपूर्ण संग्रह के लिए एक java iterator लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संपूर्ण संग्रह को निर्दिष्ट array में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाने वाला मान लौटाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक synchronization root लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**
[IChartSeries](../../com.aspose.slides/ichartseries) - निर्दिष्ट इंडेक्स पर तत्व।
### size() {#size--}
```
public final int size()
```


संग्रह में वस्तुओं की संख्या लौटाता है। केवल-पठन योग्य int.

**वापसी मान:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```


नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | सीरीज़ का प्रकार |

**वापसी मान:**
[IChartSeries](../../com.aspose.slides/ichartseries) - नया चार्ट सीरीज़।
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```


नया चार्ट सीरीज़ बनाता है और इसे संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**वापसी मान:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


[ChartDataCell](../../com.aspose.slides/chartdatacell) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | वह सेल जिसमें सीरीज़ नाम होता है। |
| type | int | सीरीज़ का प्रकार निर्धारित करने वाला मान

--------------------

यदि समान सेल से निर्मित चार्ट सीरीज़ पहले से संग्रह में मौजूद है, तो मेथड कुछ नहीं जोड़ता और इसका सूचकांक लौटाता है। |

**वापसी मान:**
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट सीरीज़ या वह सीरीज़ जो पहले से संग्रह में है।
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


[ChartCellCollection](../../com.aspose.slides/chartcellcollection) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | वे सेल जिनमें सीरीज़ नाम होते हैं। |
| type | int | सीरीज़ का प्रकार निर्धारित करने वाला मान

--------------------

यदि समान सेल से निर्मित चार्ट सीरीज़ पहले से संग्रह में मौजूद है, तो मेथड कुछ नहीं जोड़ता और इसका सूचकांक लौटाता है। |

**वापसी मान:**
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट सीरीज़ या वह सीरीज़ जो पहले से संग्रह में है।
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```


मान से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सीरीज़ नाम। |
| type | int | सीरीज़ का प्रकार निर्धारित करने वाला मान |

**वापसी मान:**
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट सीरीज़।
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```


निर्दिष्ट [ChartSeries](../../com.aspose.slides/chartseries) को खोजता है और संपूर्ण Collection के भीतर प्रथम प्रकट होने का शून्य-आधारित सूचकांक लौटाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | चार्ट सीरीज़ मान। |

**वापसी मान:**
int - यदि मिला तो संपूर्ण CollectionBase में मान की प्रथम प्रकट होने का शून्य-आधारित सूचकांक; अन्यथा -1।
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```


निर्दिष्ट मान को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | वह मान। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


निर्दिष्ट स्थिति पर संग्रह से संग्रहीत ActiveX नियंत्रण को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले नियंत्रण का सूचकांक। |

### clear() {#clear--}
```
public final void clear()
```


संग्रह से सभी नियंत्रणों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```


एक enumerator लौटाता है जो संग्रह के माध्यम से पुनरावृत करता है।

**वापसी मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - एक IGenericEnumerator जिसे संग्रह के माध्यम से पुनरावृत करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```


संपूर्ण संग्रह के लिए एक java iterator लौटाता है।

**वापसी मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - पूरी संग्रह के लिए java.util.Iterator।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


पूरे संग्रह को निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य array |
| index | int | लक्ष्य array में सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। केवल-पठन योग्य boolean।

**वापसी मान:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक synchronization root लौटाता है। केवल-पठन योग्य Object।

**वापसी मान:**
java.lang.Object