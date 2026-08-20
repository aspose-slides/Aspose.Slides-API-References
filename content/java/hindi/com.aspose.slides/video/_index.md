---
title: Video
second_title: Aspose.Slides for Java API संदर्भ
description: प्रेज़ेंटेशन में एम्बेड की गई एक छवि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/video/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

प्रेज़ेंटेशन में एम्बेड की गई एक छवि का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getContentType()](#getContentType--) | एक वीडियो का MIME प्रकार लौटाता है, जो (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। |
| [getBinaryData()](#getBinaryData--) | ऑडियो डेटा की प्रतिलिपि लौटाता है। |
| [getStream()](#getStream--) | पढ़ने के लिए Stream स्ट्रीम लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


एक वीडियो का MIME प्रकार लौटाता है, जो (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। केवल-पढ़ने-योग्य String.

**रिटर्न:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


ऑडियो डेटा की प्रतिलिपि लौटाता है। बड़ी मात्रा में डेटा के मामले में \#getStream.getStream मेथड का उपयोग करने पर विचार करें ताकि वीडियो डेटा को मेमोरी में अनावश्यक रूप से लोड करने या OutOfMemoryException जैसी त्रुटि से बचा जा सके। केवल-पढ़ने-योग्य byte[].

**रिटर्न:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


पढ़ने के लिए Stream स्ट्रीम लौटाता है। उपयोग करने के बाद 'using' का प्रयोग करें या स्ट्रीम को बंद करें।

**रिटर्न:**
java.io.InputStream - पढ़ने के लिए स्ट्रीम।
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject