---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: SmartArt आरेख के नोड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

SmartArt आरेख के नोड का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | वर्तमान नोड के सभी चाइल्ड नोड्स के संग्रह लौटाता है। |
| [getShapes()](#getShapes--) | नोड से जुड़े सभी शैप्स के संग्रह लौटाता है। |
| [getTextFrame()](#getTextFrame--) | नोड के टेक्स्ट को प्राप्त करता है या सेट करता है। |
| [isAssistant()](#isAssistant--) | नोड को सहायक (assistant) के रूप में प्राप्त करता है या सेट करता है। |
| [setAssistant(boolean value)](#setAssistant-boolean-) | नोड को सहायक (assistant) के रूप में प्राप्त करता है या सेट करता है। |
| [getLevel()](#getLevel--) | नोड का नेस्टिंग लेवल लौटाता है। |
| [getBulletFillFormat()](#getBulletFillFormat--) | नोड बुलेट के लिए फिल फ़ॉर्मेट प्रॉपर्टीज़ वाला FillFormat ऑब्जेक्ट लौटाता है। |
| [getPosition()](#getPosition--) | सिब्लिंग नोड्स में नोड का शून्य-आधारित पद प्राप्त करता है या सेट करता है। |
| [setPosition(int value)](#setPosition-int-) | सिब्लिंग नोड्स में नोड का शून्य-आधारित पद प्राप्त करता है या सेट करता है। |
| [isHidden()](#isHidden--) | यदि यह नोड डेटा मॉडल में छिपा नोड है तो true लौटाता है। |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | वर्तमान नोड से जुड़े ऑर्गेनाइजेशन चार्ट लेआउट प्रकार को प्राप्त करता है या सेट करता है। |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | वर्तमान नोड से जुड़े ऑर्गेनाइजेशन चार्ट लेआउट प्रकार को प्राप्त करता है या सेट करता है। |
| [remove()](#remove--) | वर्तमान नोड को हटाएँ। |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

वर्तमान नोड के सभी चाइल्ड नोड्स के संग्रह लौटाता है। केवल-पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**वापसी:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

नोड से जुड़े सभी शैप्स के संग्रह लौटाता है। केवल-पढ़ने योग्य [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**वापसी:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

नोड के टेक्स्ट को प्राप्त करता है या सेट करता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe).

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

नोड को सहायक (assistant) के रूप में प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

नोड को सहायक (assistant) के रूप में प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

नोड का नेस्टिंग लेवल लौटाता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

नोड बुलेट के लिए फिल फ़ॉर्मेट प्रॉपर्टीज़ वाला FillFormat ऑब्जेक्ट लौटाता है। नोट: कुछ SmartArt लेआउट के लिए यह null भी हो सकता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

सिब्लिंग नोड्स में नोड का शून्य-आधारित पद प्राप्त करता है या सेट करता है। पढ़ें/लिखें int.

**वापसी:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

सिब्लिंग नोड्स में नोड का शून्य-आधारित पद प्राप्त करता है या सेट करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

यदि यह नोड डेटा मॉडल में छिपा नोड है तो true लौटाता है। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

वर्तमान नोड से जुड़े ऑर्गेनाइजेशन चार्ट लेआउट प्रकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**वापसी:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

वर्तमान नोड से जुड़े ऑर्गेनाइजेशन चार्ट लेआउट प्रकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

वर्तमान नोड को हटाएँ।

**वापसी:**
boolean - यदि सफलतापूर्वक हटाया गया तो true, अन्यथा false.