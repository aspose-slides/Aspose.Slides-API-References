---
title: SmartArtNode
second_title: Aspose.Slides for Java API संदर्भ
description: एक SmartArt ऑब्जेक्ट का नोड दर्शाता है
type: docs
url: /hi/com.aspose.slides/smartartnode/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

SmartArt ऑब्जेक्ट का नोड दर्शाता है
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | वर्तमान नोड के सभी बाल नोड्स के संग्रह को लौटाता है। |
| [getShapes()](#getShapes--) | नोड से जुड़े सभी आकारों के संग्रह को लौटाता है। |
| [getTextFrame()](#getTextFrame--) | नोड का टेक्स्ट फ्रेम लौटाता है। |
| [isAssistant()](#isAssistant--) | नोड को सहायक के रूप में लौटाता या सेट करता है। |
| [setAssistant(boolean value)](#setAssistant-boolean-) | नोड को सहायक के रूप में लौटाता या सेट करता है। |
| [getLevel()](#getLevel--) | नोड के नेस्टिंग स्तर को लौटाता है। |
| [getBulletFillFormat()](#getBulletFillFormat--) | नोड बुलेट के लिए फ़िल फ़ॉर्मेट गुणों को सम्मिलित करने वाले FillFormat ऑब्जेक्ट को लौटाता है। |
| [getPosition()](#getPosition--) | सिब्लिंग नोड्स में नोड की शून्य-आधारित स्थिति को लौटाता या सेट करता है। |
| [setPosition(int value)](#setPosition-int-) | सिब्लिंग नोड्स में नोड की शून्य-आधारित स्थिति को लौटाता या सेट करता है। |
| [isHidden()](#isHidden--) | यदि यह नोड डेटा मॉडल में एक छिपा नोड है तो true लौटाता है। |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | वर्तमान नोड से जुड़े ऑर्गेनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता या सेट करता है। |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | वर्तमान नोड से जुड़े ऑर्गेनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता या सेट करता है। |
| [remove()](#remove--) | वर्तमान नोड को हटाता है। |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

वर्तमान नोड के सभी बाल नोड्स के संग्रह को लौटाता है। केवल पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**वापसी:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

नोड से जुड़े सभी आकारों के संग्रह को लौटाता है। केवल पढ़ने योग्य [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**वापसी:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

नोड का टेक्स्ट फ्रेम लौटाता है। केवल पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe).

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

नोड को सहायक के रूप में लौटाता या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

नोड को सहायक के रूप में लौटाता या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

नोड के नेस्टिंग स्तर को लौटाता है। केवल पढ़ने योग्य int।

**वापसी:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

नोड बुलेट के लिए फ़िल फ़ॉर्मेट गुणों को सम्मिलित करने वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के SmartArt लेआउट के लिए जो नोड्स के लिए बुलेट नहीं प्रदान करते, null लौटा सकता है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

सिब्लिंग नोड्स में नोड की शून्य-आधारित स्थिति को लौटाता या सेट करता है। पढ़ने/लिखने योग्य int।

**वापसी:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

सिब्लिंग नोड्स में नोड की शून्य-आधारित स्थिति को लौटाता या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

यदि यह नोड डेटा मॉडल में एक छिपा नोड है तो true लौटाता है। केवल पढ़ने योग्य बूलियन।

**वापसी:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

वर्तमान नोड से जुड़े ऑर्गेनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)।

**वापसी:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

वर्तमान नोड से जुड़े ऑर्गेनाइज़ेशन चार्ट लेआउट प्रकार को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

वर्तमान नोड को हटाता है।

**वापसी:**
boolean - यदि सफलतापूर्वक हटाया गया तो true, अन्यथा false