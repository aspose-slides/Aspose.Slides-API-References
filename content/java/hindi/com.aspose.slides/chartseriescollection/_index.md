---
title: ChartSeriesCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: कलेक्शन का प्रतिनिधित्व करता है
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

[ChartSeries](../../com.aspose.slides/chartseries) का संग्रह दर्शाता है

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [size()](#size--) | संग्रह में वस्तुओं की संख्या लौटाता है। |
| [add(int type)](#add-int-) | नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [insert(int index, int type)](#insert-int-int-) | नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | [ChartDataCell](../../com.aspose.slides/chartdatacell) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | [ChartCellCollection](../../com.aspose.slides/chartcellcollection) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [add(String name, int type)](#add-java.lang.String-int-) | मान से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है। |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | निर्दिष्ट [ChartSeries](../../com.aspose.slides/chartseries) की खोज करता है और पूरे संग्रह में पहली उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है। |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट स्थिति पर संग्रह में संग्रहीत ActiveX नियंत्रण को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी नियंत्रणों को हटाता है। |
| [iterator()](#iterator--) | एक एनीयरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | पूरे संग्रह को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समक्रमण रूट लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[IChartSeries](../../com.aspose.slides/ichartseries) - निर्दिष्ट इंडेक्स पर तत्व।

### size() {#size--}
```
public final int size()
```

संग्रह में वस्तुओं की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | Series का प्रकार |

**रिटर्न:**  
[IChartSeries](../../com.aspose.slides/ichartseries) - नया चार्ट सीरीज़।

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**रिटर्न:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

[ChartDataCell](../../com.aspose.slides/chartdatacell) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Series नाम वाला सेल। |
| type | int | Series का प्रकार सेट करता है |

--------------------

यदि चार्ट श्रृंखला उसी सेल से पहले से संग्रह में मौजूद है, तो विधि कुछ नहीं जोड़ती और उसका इंडेक्स लौटाती है। |

**रिटर्न:**  
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट सीरीज़ या जो पहले से संग्रह में है।

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

[ChartCellCollection](../../com.aspose.slides/chartcellcollection) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Series नाम वाले सेल्स। |
| type | int | Series का प्रकार सेट करता है |

--------------------

यदि चार्ट श्रृंखला उसी सेल से पहले से संग्रह में मौजूद है, तो विधि कुछ नहीं जोड़ती और उसका इंडेक्स लौटाती है। |

**रिटर्न:**  
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट सीरीज़ या जो पहले से संग्रह में है।

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

मान से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | Series का नाम। |
| type | int | Series का प्रकार सेट करता है |

**रिटर्न:**  
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट सीरीज़।

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

निर्दिष्ट [ChartSeries](../../com.aspose.slides/chartseries) की खोज करता है और पूरे संग्रह में पहली उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | चार्ट सीरीज़ मान। |

**रिटर्न:**  
int - यदि मिला तो पूरे CollectionBase में मान की पहली उपस्थिति का शून्य-आधारित इंडेक्स; अन्यथा -1।

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

निर्दिष्ट मान को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | मान। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट स्थिति पर संग्रह में संग्रहीत ActiveX नियंत्रण को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए नियंत्रण का इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```

सभी नियंत्रणों को संग्रह से हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

एक एनीयरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - पूरे संग्रह के लिए java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

पूरे संग्रह को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे |
| index | int | लक्ष्य एरे में इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सेफ) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समक्रमण रूट लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**  
java.lang.Object