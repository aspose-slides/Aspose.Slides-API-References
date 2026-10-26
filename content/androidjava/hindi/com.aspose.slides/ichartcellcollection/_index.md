---
title: IChartCellCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: डेटा वाली कोशिकाओं का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ichartcellcollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

डेटा वाली कोशिकाओं का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | वर्कबुक में कोशिकाओं के सेट का पता लौटाता है। |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | सभी कोशिकाओं के स्ट्रिंग मानों से संयोजन स्ट्रिंग बनाता है। |
| [get_Item(int index)](#get-Item-int-) | सूचकांक द्वारा एक कोशिका (IChartDataCell) लौटाता है। |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | संग्रह में नई कोशिका जोड़ता है। |
| [add(Object value)](#add-java.lang.Object-) | निर्दिष्ट मान से [IChartDataCell](../../com.aspose.slides/ichartdatacell) बनाता है और इसे संग्रह में जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | सूचकांक द्वारा संग्रह से एक कोशिका हटाता है। |
| [getCount()](#getCount--) | संग्रह में कोशिकाओं की गिनती प्राप्त करता है। |

### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

वर्कबुक में कोशिकाओं के सेट का पता लौटाता है।

**वापसी:**
java.lang.String - Address of the set of cells in workbook String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

सभी कोशिकाओं के स्ट्रिंग मानों से संयोजन स्ट्रिंग बनाता है।

**वापसी:**
java.lang.String - Resulting string String

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

सूचकांक द्वारा एक कोशिका (IChartDataCell) लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कोशिका का सूचकांक। |

**वापसी:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - डेटा वाली कोशिका।

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

संग्रह में नई कोशिका जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | जोड़ने के लिये नई कोशिका। |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

निर्दिष्ट मान से [IChartDataCell](../../com.aspose.slides/ichartdatacell) बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object | मान।

--------------------

यह विधि AUTO_DATA नाम की कार्यपत्रिका जोड़ती है और सभी मान वहाँ रखती है। यदि आप [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) का प्रयोग करके Cell मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्रिका का उपयोग न करें। इस विधि द्वारा जोड़े जाने वाले मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

सूचकांक द्वारा संग्रह से एक कोशिका हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने योग्य कोशिका का सूचकांक। |

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में कोशिकाओं की गिनती प्राप्त करता है। केवल पढ़ने योग्य int.

**वापसी:**
int