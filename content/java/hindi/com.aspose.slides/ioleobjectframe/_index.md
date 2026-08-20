---
title: IOleObjectFrame
second_title: Aspose.Slides for Java API संदर्भ
description: एक स्लाइड पर OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ioleobjectframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Represents an OLE object on a slide.
## विधियां

| विधि | विवरण |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट वापस करता है। |
| [getObjectName()](#getObjectName--) | ऑब्जेक्ट का नाम वापस करता है या सेट करता है। |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | ऑब्जेक्ट का नाम वापस करता है या सेट करता है। |
| [getEmbeddedData()](#getEmbeddedData--) | OLE एंबेडेड डेटा के बारे में जानकारी प्राप्त करता है। |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE एंबेडेड डेटा के बारे में जानकारी सेट करता है। |
| [getObjectProgId()](#getObjectProgId--) | ऑब्जेक्ट का ProgID वापस करता है। |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | ऑब्जेक्ट का ProgID वापस करता है। |
| [getLinkFileName()](#getLinkFileName--) | लिंक्ड फ़ाइल के पूर्ण पथ को वापस करता है। |
| [getLinkPathLong()](#getLinkPathLong--) | लिंक्ड फ़ाइल के पूर्ण पथ को वापस करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | लिंक्ड फ़ाइल के पूर्ण पथ को वापस करता है। |
| [getLinkPathRelative()](#getLinkPathRelative--) | यदि मौजूद हो तो लिंक्ड फ़ाइल का सापेक्ष पथ वापस करता है, अन्यथा खाली स्ट्रिंग लौटाता है। |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | एंबेडेड OLE ऑब्जेक्ट का फ़ाइल नाम वापस करता है। |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | एंबेडेड OLE ऑब्जेक्ट का पथ वापस करता है। |
| [isObjectIcon()](#isObjectIcon--) | निर्धारित करता है कि क्या ऑब्जेक्ट आइकॉन के रूप में दिखाई देता है। |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | निर्धारित करता है कि क्या ऑब्जेक्ट आइकॉन के रूप में दिखाई देता है। |
| [isObjectLink()](#isObjectLink--) | निर्धारित करता है कि क्या ऑब्जेक्ट बाहरी फ़ाइल से लिंक्ड है। |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | निर्धारित करता है कि लिंक्ड एंबेडेड ऑब्जेक्ट प्रस्तुति खुले या प्रिंट होने पर स्वचालित रूप से अपडेट होता है या नहीं। |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | निर्धारित करता है कि लिंक्ड एंबेडेड ऑब्जेक्ट प्रस्तुति खुले या प्रिंट होने पर स्वचालित रूप से अपडेट होता है या नहीं। |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject आइकॉन के लिए शीर्षक वापस करता है या सेट करता है। |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject आइकॉन के लिए शीर्षक वापस करता है या सेट करता है। |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट वापस करता है। केवल पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)।

**वापसी:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

ऑब्जेक्ट का नाम वापस करता है या सेट करता है। पढ़ें/लिखें String।

**वापसी:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

ऑब्जेक्ट का नाम वापस करता है या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

OLE एंबेडेड डेटा के बारे में जानकारी प्राप्त करता है। केवल पढ़ने योग्य [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)।

**वापसी:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

OLE एंबेडेड डेटा के बारे में जानकारी सेट करता है।

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | एम्बेडेड डेटा [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

यह मेथड ऑब्जेक्ट की प्रॉपर्टीज़ को नई डेटा के अनुसार बदलता है और IsObjectLink फ़्लैग को false सेट करता है, यह दर्शाते हुए कि OLE ऑब्जेक्ट एंबेडेड है। |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

ऑब्जेक्ट का ProgID वापस करता है। केवल पढ़ने योग्य String।

**वापसी:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

ऑब्जेक्ट का ProgID वापस करता है। केवल पढ़ने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

लिंक्ड फ़ाइल के पूर्ण पथ को वापस करता है। छोटा फ़ाइल नाम उपयोग किया जाएगा। केवल पढ़ने योग्य String।

**वापसी:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

लिंक्ड फ़ाइल के पूर्ण पथ को वापस करता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ें/लिखें String।

**वापसी:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

लिंक्ड फ़ाइल के पूर्ण पथ को वापस करता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

यदि मौजूद हो तो लिंक्ड फ़ाइल का सापेक्ष पथ वापस करता है, अन्यथा खाली स्ट्रिंग लौटाता है। केवल पढ़ने योग्य String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

Ppt प्रस्तुतियों में, कुछ Ole ऑब्जेक्ट लिंक सापेक्ष प्रतिनिधित्व रख सकते हैं।

**वापसी:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

एंबेडेड OLE ऑब्जेक्ट का फ़ाइल नाम वापस करता है

**वापसी:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

एंबेडेड OLE ऑब्जेक्ट का पथ वापस करता है

**वापसी:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

निर्धारित करता है कि क्या ऑब्जेक्ट आइकॉन के रूप में दिखाई देता है। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

निर्धारित करता है कि क्या ऑब्जेक्ट आइकॉन के रूप में दिखाई देता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

निर्धारित करता है कि क्या ऑब्जेक्ट बाहरी फ़ाइल से लिंक्ड है। केवल पढ़ने योग्य boolean.

**वापसी:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

निर्धारित करता है कि लिंक्ड एंबेडेड ऑब्जेक्ट प्रस्तुति खुले या प्रिंट होने पर स्वचालित रूप से अपडेट होता है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

निर्धारित करता है कि लिंक्ड एंबेडेड ऑब्जेक्ट प्रस्तुति खुले या प्रिंट होने पर स्वचालित रूप से अपडेट होता है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

OleObject आइकॉन के लिए शीर्षक वापस करता है या सेट करता है। पढ़ें/लिखें String.

--------------------

जब IsObjectIcon == false हो तो यह मान अनदेखा किया जाता है। स्ट्रिंग को OLE आइकॉन के आकार के अनुसार काटा जा सकता है।

**वापसी:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

OleObject आइकॉन के लिए शीर्षक वापस करता है या सेट करता है। पढ़ें/लिखें String.

--------------------

जब IsObjectIcon == false हो तो यह मान अनदेखा किया जाता है। स्ट्रिंग को OLE आइकॉन के आकार के अनुसार काटा जा सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |