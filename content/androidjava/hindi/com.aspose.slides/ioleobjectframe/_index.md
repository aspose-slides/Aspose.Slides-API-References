---
title: IOleObjectFrame
second_title: Android के लिए Aspose.Slides, Java API संदर्भ के माध्यम से
description: स्लाइड पर एक OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ioleobjectframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

एक स्लाइड पर OLE ऑब्जेक्ट को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट को लौटाता है। |
| [getObjectName()](#getObjectName--) | ऑब्जेक्ट का नाम लौटाता है या सेट करता है। |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | ऑब्जेक्ट का नाम लौटाता है या सेट करता है। |
| [getEmbeddedData()](#getEmbeddedData--) | OLE एम्बेडेड डेटा के बारे में जानकारी प्राप्त करता है। |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है। |
| [getObjectProgId()](#getObjectProgId--) | ऑब्जेक्ट का ProgID लौटाता है। |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | ऑब्जेक्ट का ProgID लौटाता है। |
| [getLinkFileName()](#getLinkFileName--) | लिंक्ड फ़ाइल का पूरा पथ लौटाता है। |
| [getLinkPathLong()](#getLinkPathLong--) | लिंक्ड फ़ाइल का पूरा पथ लौटाता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | लिंक्ड फ़ाइल का पूरा पथ लौटाता है। |
| [getLinkPathRelative()](#getLinkPathRelative--) | यदि उपलब्ध हो तो लिंक्ड फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | एम्बेडेड OLE ऑब्जेक्ट का फ़ाइल नाम लौटाता है। |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | एम्बेडेड OLE ऑब्जेक्ट का पथ लौटाता है। |
| [isObjectIcon()](#isObjectIcon--) | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दृश्यमान है या नहीं। |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दृश्यमान है या नहीं। |
| [isObjectLink()](#isObjectLink--) | निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से जुड़ा है या नहीं। |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | निर्धारित करता है कि प्रस्तुति खोलने या प्रिंट करने पर लिंक्ड एम्बेडेड ऑब्जेक्ट स्वचालित रूप से अपडेट होता है या नहीं। |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | निर्धारित करता है कि प्रस्तुति खोलने या प्रिंट करने पर लिंक्ड एम्बेडेड ऑब्जेक्ट स्वचालित रूप से अपडेट होता है या नहीं। |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject आइकन के शीर्षक को लौटाता है या सेट करता है। |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject आइकन के शीर्षक को लौटाता है या सेट करता है। |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)।

**रिटर्न:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


ऑब्जेक्ट का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


ऑब्जेक्ट का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


OLE एम्बेडेड डेटा के बारे में जानकारी प्राप्त करता है। केवल पढ़ने योग्य [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)।

**रिटर्न:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है।

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
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | एम्बेडेड डेटा [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

--------------------

यह मेथड ऑब्जेक्ट की प्रॉपर्टीज़ को नए डेटा को दर्शाने के लिए बदलता है और IsObjectLink फ़्लैग को false सेट करता है, यह संकेत देते हुए कि OLE ऑब्जेक्ट एम्बेडेड है। |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


ऑब्जेक्ट का ProgID लौटाता है। केवल पढ़ने योग्य String।

**रिटर्न:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


ऑब्जेक्ट का ProgID लौटाता है। केवल पढ़ने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


लिंक्ड फ़ाइल का पूरा पथ लौटाता है। छोटा फ़ाइल नाम उपयोग किया जाएगा। केवल पढ़ने योग्य String।

**रिटर्न:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


लिंक्ड फ़ाइल का पूरा पथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


लिंक्ड फ़ाइल का पूरा पथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```


यदि उपलब्ध हो तो लिंक्ड फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। केवल पढ़ने योग्य String।

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

Ppt प्रस्तुतियों में, कुछ Ole ऑब्जेक्ट लिंक का सापेक्ष प्रतिनिधित्व हो सकता है।

**रिटर्न:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


एम्बेडेड OLE ऑब्जेक्ट का फ़ाइल नाम लौटाता है।

**रिटर्न:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


एम्बेडेड OLE ऑब्जेक्ट का पथ लौटाता है।

**रिटर्न:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दृश्यमान है या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दृश्यमान है या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से जुड़ा है या नहीं। केवल पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


निर्धारित करता है कि प्रस्तुति खोलने या प्रिंट करने पर लिंक्ड एम्बेडेड ऑब्जेक्ट स्वचालित रूप से अपडेट होता है या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


निर्धारित करता है कि प्रस्तुति खोलने या प्रिंट करने पर लिंक्ड एम्बेडेड ऑब्जेक्ट स्वचालित रूप से अपडेट होता है या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


OleObject आइकन के शीर्षक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

--------------------

जब IsObjectIcon == false हो तो यह मान अनदेखा किया जाता है। स्ट्रिंग को OLE आइकन के आकार के अनुसार छोटा किया जा सकता है।

**रिटर्न:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


OleObject आइकन के शीर्षक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

--------------------

जब IsObjectIcon == false हो तो यह मान अनदेखा किया जाता है। स्ट्रिंग को OLE आइकन के आकार के अनुसार छोटा किया जा सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |