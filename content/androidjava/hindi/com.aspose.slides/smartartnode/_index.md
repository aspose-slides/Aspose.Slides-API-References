---
title: SmartArtNode
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस
description: SmartArt ऑब्जेक्ट का नोड दर्शाता है
type: docs
url: /hi/com.aspose.slides/smartartnode/
---
**विरासत:**  
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)  
```
public final class SmartArtNode implements ISmartArtNode
```

SmartArt ऑब्जेक्ट का नोड दर्शाता है  
## विधाएँ

| मेथड | विवरण |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | वर्तमान नोड के सभी चाइल्ड नोड्स के संग्रह लौटाता है। |
| [getShapes()](#getShapes--) | नोड से जुड़े सभी शेप्स के संग्रह लौटाता है। |
| [getTextFrame()](#getTextFrame--) | नोड का टेक्स्ट फ्रेम लौटाता है। |
| [isAssistant()](#isAssistant--) | नोड को असिस्टेंट के रूप में लौटाता है या सेट करता है। |
| [setAssistant(boolean value)](#setAssistant-boolean-) | नोड को असिस्टेंट के रूप में लौटाता है या सेट करता है। |
| [getLevel()](#getLevel--) | नोड का नेस्टिंग लेवल लौटाता है। |
| [getBulletFillFormat()](#getBulletFillFormat--) | नोड बुलेट के लिए फ़िल फ़ॉर्मेट प्रॉपर्टीज़ रखने वाले FillFormat ऑब्जेक्ट को लौटाता है। |
| [getPosition()](#getPosition--) | भाई-बहन नोड्स में नोड की शून्य-आधारित स्थिति लौटाता है या सेट करता है। |
| [setPosition(int value)](#setPosition-int-) | भाई-बहन नोड्स में नोड की शून्य-आधारित स्थिति लौटाता है या सेट करता है। |
| [isHidden()](#isHidden--) | यदि यह नोड डेटा मॉडल में छिपा नोड है तो true लौटाता है। |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | वर्तमान नोड से जुड़े ऑर्गनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता है या सेट करता है। |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | वर्तमान नोड से जुड़े ऑर्गनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता है या सेट करता है। |
| [remove()](#remove--) | वर्तमान नोड को हटाएँ। |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

वर्तमान नोड के सभी चाइल्ड नोड्स के संग्रह लौटाता है। केवल पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)।

**रिटर्न:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

नोड से जुड़े सभी शेप्स के संग्रह लौटाता है। केवल पढ़ने योग्य [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)।

**रिटर्न:**  
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

नोड का टेक्स्ट फ्रेम लौटाता है। केवल पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

नोड को असिस्टेंट के रूप में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**  
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

नोड को असिस्टेंट के रूप में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

नोड का नेस्टिंग लेवल लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**  
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

नोड बुलेट के लिए फ़िल फ़ॉर्मेट प्रॉपर्टीज़ रखने वाले FillFormat ऑब्जेक्ट को लौटाता है। ध्यान दें: कुछ प्रकार के SmartArt लेआउट के लिए जो नोड्स के बुलेट प्रदान नहीं करते, null लौटाया जा सकता है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

भाई-बहन नोड्स में नोड की शून्य-आधारित स्थिति लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

भाई-बहन नोड्स में नोड की शून्य-आधारित स्थिति लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

यदि यह नोड डेटा मॉडल में छिपा नोड है तो true लौटाता है। केवल पढ़ने योग्य boolean।

**रिटर्न:**  
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

वर्तमान नोड से जुड़े ऑर्गनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)।

**रिटर्न:**  
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

वर्तमान नोड से जुड़े ऑर्गनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

वर्तमान नोड को हटाएँ।

**रिटर्न:**  
boolean - यदि सफलतापूर्वक हटाया गया तो true, अन्यथा false