---
title: ISmartArtNode
second_title: Aspose.Slides for Java API संदर्भ
description: SmartArt आरेख के नोड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

SmartArt आरेख के नोड का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | वर्तमान नोड के सभी चाइल्ड नोड्स के संग्रह लौटाता है। |
| [getShapes()](#getShapes--) | नोड से जुड़े सभी शैप्स के संग्रह लौटाता है। |
| [getTextFrame()](#getTextFrame--) | नोड का टेक्स्ट लौटाता है या सेट करता है। |
| [isAssistant()](#isAssistant--) | नोड को सहायक के रूप में लौटाता है या सेट करता है। |
| [setAssistant(boolean value)](#setAssistant-boolean-) | नोड को सहायक के रूप में लौटाता है या सेट करता है। |
| [getLevel()](#getLevel--) | नोड के नेस्टिंग लेवल को लौटाता है। |
| [getBulletFillFormat()](#getBulletFillFormat--) | नोड बुलेट के लिए फ़िल फ़ॉर्मेट गुणों को समाहित करने वाले FillFormat ऑब्जेक्ट को लौटाता है। |
| [getPosition()](#getPosition--) | भाई-भतीजे नोड्स में नोड की शून्य-आधारित स्थिति को लौटाता है या सेट करता है। |
| [setPosition(int value)](#setPosition-int-) | भाई-भतीजे नोड्स में नोड की शून्य-आधारित स्थिति को लौटाता है या सेट करता है। |
| [isHidden()](#isHidden--) | यदि यह नोड डेटा मॉडल में छिपा नोड है तो true लौटाता है। |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | वर्तमान नोड से जुड़े ऑर्गेनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता है या सेट करता है। |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | वर्तमान नोड से जुड़े ऑर्गेनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता है या सेट करता है। |
| [remove()](#remove--) | वर्तमान नोड को हटाता है। |

### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

वर्तमान नोड के सभी चाइल्ड नोड्स के संग्रह लौटाता है। केवल-पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)।

**वापसी:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

नोड से जुड़े सभी शैप्स के संग्रह लौटाता है। केवल-पढ़ने योग्य [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)।

**वापसी:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

नोड का टेक्स्ट लौटाता है या सेट करता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)

### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

नोड को सहायक के रूप में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

**वापसी:**
boolean

### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

नोड को सहायक के रूप में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

नोड के नेस्टिंग लेवल को लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int

### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

नोड बुलेट के लिए फ़िल फ़ॉर्मेट गुणों को समाहित करने वाले FillFormat ऑब्जेक्ट को लौटाता है। ध्यान दें: कुछ SmartArt लेआउट के लिए यह null लौट सकता है जिसमें नोड्स के लिए बुलेट नहीं होते हैं। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

भाई-भतीजे नोड्स में नोड की शून्य-आधारित स्थिति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**वापसी:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

भाई-भतीजे नोड्स में नोड की शून्य-आधारित स्थिति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

यदि यह नोड डेटा मॉडल में छिपा नोड है तो true लौटाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean

### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

वर्तमान नोड से जुड़े ऑर्गेनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)।

**वापसी:**
int

### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

वर्तमान नोड से जुड़े ऑर्गेनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public abstract boolean remove()
```

वर्तमान नोड को हटाता है।

**वापसी:**
boolean - true if removed succesfully, otherwise false.