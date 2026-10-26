---
title: IAutoShape
second_title: Aspose.Slides for Java API संदर्भ
description: AutoShape का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iautoshape/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

AutoShape का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | AutoShape के लॉक लौटाता है। |
| [getTextFrame()](#getTextFrame--) | AutoShape के लिए TextFrame वस्तु लौटाता है। |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | निर्धारित करता है कि क्या इस autoshape को शैली या फ़िल फ़ॉर्मेट द्वारा निर्दिष्ट करने के बजाय स्लाइड की पृष्ठभूमि फ़िल से भरना चाहिए। |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | निर्धारित करता है कि क्या इस autoshape को शैली या फ़िल फ़ॉर्मेट द्वारा निर्दिष्ट करने के बजाय स्लाइड की पृष्ठभूमि फ़िल से भरना चाहिए। |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | एक आकार में नया TextFrame जोड़ता है। |
| [isTextBox()](#isTextBox--) | निर्देशित करता है कि आकार एक टेक्स्ट बॉक्स है या नहीं। |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

AutoShape के लॉक लौटाता है। केवल पढ़ने योग्य [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)।

**वापसी:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

AutoShape के लिए TextFrame वस्तु लौटाता है। केवल पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

निर्धारित करता है कि क्या इस autoshape को शैली या फ़िल फ़ॉर्मेट द्वारा निर्दिष्ट करने के बजाय स्लाइड की पृष्ठभूमि फ़िल से भरना चाहिए। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

निर्धारित करता है कि क्या इस autoshape को शैली या फ़िल फ़ॉर्मेट द्वारा निर्दिष्ट करने के बजाय स्लाइड की पृष्ठभूमि फ़िल से भरना चाहिए। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

एक आकार में नया TextFrame जोड़ता है। यदि आकार में पहले से TextFrame है तो केवल उसका टेक्स्ट बदल दिया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | एक नया TextFrame के लिए डिफ़ॉल्ट टेक्स्ट। |

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe) - नया [ITextFrame](../../com.aspose.slides/itextframe) वस्तु।
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

निर्देशित करता है कि आकार एक टेक्स्ट बॉक्स है या नहीं।

--------------------

यदि आकार को टेक्स्ट बॉक्स के रूप में निर्दिष्ट नहीं किया गया है, तो इसका अर्थ यह नहीं है कि उसमें टेक्स्ट संलग्न नहीं किया जा सकता। एक टेक्स्ट बॉक्स केवल विशिष्ट गुणों वाला विशेष आकार है।

**वापसी:**
boolean