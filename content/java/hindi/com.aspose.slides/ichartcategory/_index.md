---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: चार्ट श्रेणियों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

चार्ट श्रेणियों का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getUseCell()](#getUseCell--) | If true then AsCell property is actual. |
| [getAsCell()](#getAsCell--) | Returns or sets IChartDataCell object. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets IChartDataCell object. |
| [getAsLiteral()](#getAsLiteral--) | Returns or sets AsLiteral if UseCell is false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returns or sets AsLiteral if UseCell is false. |
| [getValue()](#getValue--) | If UseCell is true then this property represents AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | If UseCell is true then this property represents AsCell.Value property. |
| [getGroupingLevels()](#getGroupingLevels--) | Managed container of the values of the chart category grouping levels. |
| [remove()](#remove--) | Removes category from chart. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

यदि सत्य है तो AsCell प्रॉपर्टी वास्तविक है। दूसरे शब्दों में, कार्यपत्रक श्रेणी को संग्रहीत करने के लिए उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणी का समर्थन करता है)। यदि असत्य है तो AsLiteral प्रॉपर्टी वास्तविक है। दूसरे शब्दों में, कार्यपत्रक श्रेणी को संग्रहीत करने के लिए उपयोग नहीं किया जाता (और यह मामला बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। केवल-पढ़ने योग्य बूलियन।

--------------------

इस गुण का मान बदलने के लिए (सभी श्रेणियों के संग्रह में) नई मान [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) गुण पर सेट करें।

**रिटर्न:**  
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी बहु-स्तरीय है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट उपयोग किया जाता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी बहु-स्तरीय है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट उपयोग किया जाता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

यदि UseCell असत्य है तो AsLiteral को लौटाता है या सेट करता है। पढ़ें/लिखें Object।

**रिटर्न:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

यदि UseCell असत्य है तो AsLiteral को लौटाता है या सेट करता है। पढ़ें/लिखें Object।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

यदि UseCell सत्य है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाता है। यदि UseCell असत्य है तो यह प्रॉपर्टी AsLiteral प्रॉपर्टी को दर्शाता है। पढ़ें/लिखें Object।

**रिटर्न:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

यदि UseCell सत्य है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाता है। यदि UseCell असत्य है तो यह प्रॉपर्टी AsLiteral प्रॉपर्टी को दर्शाता है। पढ़ें/लिखें Object।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर। बहु-स्तरीय श्रेणियों में एक से अधिक समूह स्तर होते हैं। समूह स्तरों की अनुक्रमण शून्य-आधारित है। केवल-पढ़ने योग्य [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)।

**रिटर्न:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

चार्ट से श्रेणी हटाता है।