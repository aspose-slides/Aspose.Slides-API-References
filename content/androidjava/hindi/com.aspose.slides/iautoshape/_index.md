---
title: IAutoShape
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक AutoShape का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iautoshape/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

AutoShape का प्रतिनिधित्व करता है।
## Methods

| Method | Description |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | AutoShape के लॉक लौटाता है। |
| [getTextFrame()](#getTextFrame--) | AutoShape के लिए TextFrame वस्तु लौटाता है। |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | निर्धारित करता है कि क्या इस autoshape को शैली या fill format द्वारा निर्दिष्ट करने के बजाय स्लाइड की पृष्ठभूमि भराव से भरना चाहिए। |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | निर्धारित करता है कि क्या इस autoshape को शैली या fill format द्वारा निर्दिष्ट करने के बजाय स्लाइड की पृष्ठभूमि भराव से भरना चाहिए। |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | एक shape में नया TextFrame जोड़ता है। |
| [isTextBox()](#isTextBox--) | निर्धारित करता है कि shape एक टेक्स्ट बॉक्स है या नहीं। |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


AutoShape के लॉक लौटाता है। केवल-पढ़ने-योग्य [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)।

**Returns:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


AutoShape के लिए TextFrame वस्तु लौटाता है। केवल-पढ़ने-योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


निर्धारित करता है कि क्या इस autoshape को शैली या fill format द्वारा निर्दिष्ट करने के बजाय स्लाइड की पृष्ठभूमि भराव से भरना चाहिए। पढ़ने-लिये/लिखने-लिये बूलियन।

**Returns:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


निर्धारित करता है कि क्या इस autoshape को शैली या fill format द्वारा निर्दिष्ट करने के बजाय स्लाइड की पृष्ठभूमि भराव से भरना चाहिए। पढ़ने-लिये/लिखने-लिये बूलियन।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


एक shape में नया TextFrame जोड़ता है। यदि shape में पहले से TextFrame है तो केवल उसका पाठ बदल देता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | नए TextFrame के लिए डिफ़ॉल्ट पाठ। |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe) - नया [ITextFrame](../../com.aspose.slides/itextframe) ऑब्जेक्ट।
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


निर्धारित करता है कि shape एक टेक्स्ट बॉक्स है या नहीं।

--------------------

यदि shape को टेक्स्ट बॉक्स के रूप में निर्दिष्ट नहीं किया गया है, तो इसका यह मतलब नहीं है कि उसमें पाठ संलग्न नहीं हो सकता। एक टेक्स्ट बॉक्स केवल विशिष्ट गुणों वाला विशेष shape है।

**Returns:**
boolean