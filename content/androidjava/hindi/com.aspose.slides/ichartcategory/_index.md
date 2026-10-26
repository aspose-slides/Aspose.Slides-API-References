---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Represents chart categories.
type: docs
url: /hi/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

चार्ट श्रेणियों का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getUseCell()](#getUseCell--) | यदि सत्य हो तो AsCell संपत्ति वास्तविक है। |
| [getAsCell()](#getAsCell--) | IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getAsLiteral()](#getAsLiteral--) | यदि UseCell असत्य है तो AsLiteral को लौटाता है या सेट करता है। |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | यदि UseCell असत्य है तो AsLiteral को लौटाता है या सेट करता है। |
| [getValue()](#getValue--) | यदि UseCell सत्य है तो यह संपत्ति AsCell.Value संपत्ति को दर्शाती है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | यदि UseCell सत्य है तो यह संपत्ति AsCell.Value संपत्ति को दर्शाती है। |
| [getGroupingLevels()](#getGroupingLevels--) | चार्ट श्रेणी ग्रुपिंग स्तरों के मानों का प्रबंधित कंटेनर। |
| [remove()](#remove--) | श्रेणी को चार्ट से हटाता है। |

### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

यदि सत्य हो तो AsCell संपत्ति वास्तविक है। अन्य शब्दों में, कार्यपत्रक को श्रेणी संग्रहीत करने के लिए उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणी का समर्थन करता है)। यदि असत्य हो तो AsLiteral संपत्ति वास्तविक है। अन्य शब्दों में, कार्यपत्रक श्रेणी संग्रहीत करने के लिए उपयोग नहीं किया जाता (और यह मामला बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। केवल पढ़ने योग्य बूलियन।

--------------------

इस गुण के मान को बदलने के लिए (सभी श्रेणियों के संग्रह में) नया मान [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) गुण में सेट करें।

**वापसी:**  
boolean

### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी बहु-स्तरीय है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट का प्रयोग किया जाता है। पढ़ने/लिखने योग्य [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**वापसी:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी बहु-स्तरीय है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट का उपयोग किया जाता है। पढ़ने/लिखने योग्य [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

यदि UseCell असत्य है तो AsLiteral को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य ऑब्जेक्ट।

**वापसी:**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

यदि UseCell असत्य है तो AsLiteral को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य ऑब्जेक्ट।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

यदि UseCell सत्य है तो यह संपत्ति AsCell.Value संपत्ति को दर्शाती है। यदि UseCell असत्य है तो यह संपत्ति AsLiteral संपत्ति को दर्शाती है। पढ़ने/लिखने योग्य ऑब्जेक्ट।

**वापसी:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

यदि UseCell सत्य है तो यह संपत्ति AsCell.Value संपत्ति को दर्शाती है। यदि UseCell असत्य है तो यह संपत्ति AsLiteral संपत्ति को दर्शाती है। पढ़ने/लिखने योग्य ऑब्जेक्ट।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

चार्ट श्रेणी ग्रुपिंग स्तरों के मानों का प्रबंधित कंटेनर। बहु-स्तरीय श्रेणी में एक से अधिक ग्रुपिंग स्तर होते हैं। ग्रुपिंग स्तरों की अनुक्रमणिका शून्य-आधारित है। केवल पढ़ने योग्य [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)।

**वापसी:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### remove() {#remove--}
```
public abstract void remove()
```

श्रेणी को चार्ट से हटाता है।