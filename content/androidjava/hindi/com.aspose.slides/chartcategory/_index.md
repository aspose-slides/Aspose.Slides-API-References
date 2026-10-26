---
title: ChartCategory
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: चार्ट श्रेणियों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartcategory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

चार्ट श्रेणियों का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getUseCell()](#getUseCell--) | यदि true हो तो AsCell प्रॉपर्टी वास्तविक है। |
| [getAsCell()](#getAsCell--) | IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getValue()](#getValue--) | यदि UseCell true है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाती है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | यदि UseCell true है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाती है। |
| [getGroupingLevels()](#getGroupingLevels--) | चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर। |
| [remove()](#remove--) | श्रेणी को चार्ट से हटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

यदि true हो तो AsCell प्रॉपर्टी वास्तविक है। अन्य शब्दों में, worksheet श्रेणी को संग्रहित करने के लिए उपयोग किया जाता है (यह केस बहु-स्तरीय श्रेणी का समर्थन करता है)। यदि false हो तो AsLiteral प्रॉपर्टी वास्तविक है। अन्य शब्दों में, worksheet श्रेणी को संग्रहित करने के लिए उपयोग नहीं किया जाता (और यह केस बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। केवल-पढ़ने योग्य बूलियन.

--------------------

इस प्रॉपर्टी का मान बदलने के लिए (सभी श्रेणियों के संग्रह में) नई मान को ChartCategoryCollection.UseCells प्रॉपर्टी पर सेट करें.

**वापसी:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी बहु-स्तरीय है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट का उपयोग किया जाता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**वापसी:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी बहु-स्तरीय है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट का उपयोग किया जाता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

AsLiteral ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ें/लिखें Object.

**वापसी:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

AsLiteral ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ें/लिखें Object.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

यदि UseCell true है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाती है। यदि UseCell false है तो यह प्रॉपर्टी AsLiteral प्रॉपर्टी को दर्शाती है। पढ़ें/लिखें Object.

**वापसी:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

यदि UseCell true है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाती है। यदि UseCell false है तो यह प्रॉपर्टी AsLiteral प्रॉपर्टी को दर्शाती है। पढ़ें/लिखें Object.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर। बहु-स्तरीय श्रेणी में एक से अधिक समूह स्तर होते हैं। समूह स्तरों की अनुक्रमण शून्य-आधारित है। केवल-पढ़ने योग्य [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)।

**वापसी:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

श्रेणी को चार्ट से हटाता है।

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject