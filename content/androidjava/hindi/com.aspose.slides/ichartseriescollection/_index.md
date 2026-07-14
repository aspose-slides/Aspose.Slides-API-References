---
title: IChartSeriesCollection
second_title: Android के लिए Aspose.Slides, Java API संदर्भ
description: संग्रह का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/ichartseriescollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

[IChartSeries](../../com.aspose.slides/ichartseries) का संग्रह दर्शाता है
## विधियां

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व को प्राप्त करता है। |
| [add(int type)](#add-int-) | नया चार्ट श्रृंखला बनाता है और उसे संग्रह में जोड़ता है। |
| [insert(int index, int type)](#insert-int-int-) | नया चार्ट श्रृंखला बनाता है और उसे संग्रह में डालता है। |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | [IChartDataCell](../../com.aspose.slides/ichartdatacell) से नया चार्ट श्रृंखला बनाकर संग्रह में जोड़ता है। |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) से नया चार्ट श्रृंखला बनाकर संग्रह में जोड़ता है। |
| [add(String name, int type)](#add-java.lang.String-int-) | मान से नया चार्ट श्रृंखला बनाकर संग्रह में जोड़ता है। |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | निर्दिष्ट [IChartSeries](../../com.aspose.slides/ichartseries) को खोजता है और पूरी संग्रह में पहली बार प्रकट होने का शून्य-आधारित इंडेक्स लौटाता है। |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर तत्व को हटाता है। |
| [clear()](#clear--) | सभी तत्वों (चार्ट शैली सहित) को संग्रह से हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व को प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries) - निर्दिष्ट इंडेक्स पर तत्व।

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

नया चार्ट श्रृंखला बनाता है और उसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | श्रृंखला का प्रकार |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries) - नया चार्ट श्रृंखला।

### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

नया चार्ट श्रृंखला बनाता है और उसे संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | इंसर्शन के लिए इंडेक्स |
| type | int | चार्ट प्रकार [ChartType](../../com.aspose.slides/charttype) |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries) - नया चार्ट श्रृंखला [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

[IChartDataCell](../../com.aspose.slides/ichartdatacell) से नया चार्ट श्रृंखला बनाकर संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | सेल जिसमें श्रृंखला का नाम होता है। |
| type | int | श्रृंखला का प्रकार निर्धारित करता है |

--------------------

यदि उसी सेल से बनाया गया चार्ट श्रृंखला पहले ही संग्रह में मौजूद है, तो मेथड कुछ नहीं जोड़ता और उसका इंडेक्स लौटाता है। |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट श्रृंखला या वह श्रृंखला जो पहले से संग्रह में मौजूद है।

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) से नया चार्ट श्रृंखला बनाकर संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | सेल्स जिसमें श्रृंखला का नाम होता है। |
| type | int | श्रृंखला का प्रकार निर्धारित करता है |

--------------------

यदि उसी सेल से बनाया गया चार्ट श्रृंखला पहले ही संग्रह में मौजूद है, तो मेथड कुछ नहीं जोड़ता और उसका इंडेक्स लौटाता है। |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट श्रृंखला या वह श्रृंखला जो पहले से संग्रह में मौजूद है।

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

मान से नया चार्ट श्रृंखला बनाकर संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | श्रृंखला का नाम। |
| type | int | श्रृंखला का प्रकार निर्धारित करता है |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries) - जोड़ा गया चार्ट श्रृंखला।

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

निर्दिष्ट [IChartSeries](../../com.aspose.slides/ichartseries) को खोजता है और पूरी संग्रह में पहली बार प्रकट होने का शून्य-आधारित इंडेक्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | चार्ट श्रृंखला का मान। |

**रिटर्न:**
int - पूरी संग्रह में मान की पहली घटना का शून्य-आधारित इंडेक्स, यदि मिला; अन्यथा -1।

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

निर्दिष्ट मान को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | मान। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | इंडेक्स। |

### clear() {#clear--}
```
public abstract void clear()
```

सभी तत्वों (चार्ट शैली सहित) को संग्रह से हटाता है।