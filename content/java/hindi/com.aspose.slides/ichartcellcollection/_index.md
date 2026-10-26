---
title: IChartCellCollection
second_title: Aspose.Slides के लिए Java API रेफ़रेंस
description: डेटा वाली कोशिकाओं का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ichartcellcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

डेटा वाली कोशिकाओं का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | वर्कबुक में कोशिकाओं के सेट का पता लौटाता है। |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | सभी कोशिकाओं के स्ट्रिंग मानों से बनी संयोजन स्ट्रिंग। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा एक सेल (IChartDataCell) लौटाता है। |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | संग्रह में नया सेल जोड़ता है। |
| [add(Object value)](#add-java.lang.Object-) | [IChartDataCell](../../com.aspose.slides/ichartdatacell) को निर्दिष्ट मान से बनाता है और संग्रह में जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | इंडेक्स द्वारा संग्रह से एक सेल हटाता है। |
| [getCount()](#getCount--) | संग्रह में कोशिकाओं की गणना प्राप्त करता है। |

### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

वर्कबुक में कोशिकाओं के सेट का पता लौटाता है।

**रिटर्न:**
java.lang.String - वर्कबुक में कोशिकाओं के सेट का पता String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

सभी कोशिकाओं के स्ट्रिंग मानों से बनी संयोजन स्ट्रिंग।

**रिटर्न:**
java.lang.String - परिणामी स्ट्रिंग String

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

इंडेक्स द्वारा एक सेल (IChartDataCell) लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | एक सेल की इंडेक्स। |

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - डेटा वाला सेल।

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

संग्रह में नया सेल जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | जोड़ने के लिए नया सेल। |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

[IChartDataCell](../../com.aspose.slides/ichartdatacell) को निर्दिष्ट मान से बनाता है और संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object | मान। |

--------------------

यह विधि "AUTO_DATA" नाम के साथ वर्कशीट जोड़ती है और सभी मान वहाँ जोड़ती है। यदि आप [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) का उपयोग करके Cell मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस वर्कशीट का उपयोग न करें। इस विधि द्वारा जोड़े गए मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

इंडेक्स द्वारा संग्रह से एक सेल हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए सेल का इंडेक्स। |

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में कोशिकाओं की गिनती प्राप्त करता है। केवल-पठन int.

**रिटर्न:**
int