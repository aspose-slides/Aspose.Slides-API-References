---
title: IVideo
second_title: Aspose.Slides for Java API संदर्भ
description: एक प्रस्तुति में एम्बेड किया गया वीडियो का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ivideo/
---```
public interface IVideo
```

एक प्रस्तुति में एम्बेड किया गया वीडियो का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getContentType()](#getContentType--) | एक वीडियो का MIME प्रकार लौटाता है, जो (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। |
| [getBinaryData()](#getBinaryData--) | ऑडियो डेटा की प्रति लौटाता है। |
| [getStream()](#getStream--) | पढ़ने के लिए Stream स्ट्रीम लौटाता है। |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


एक वीडियो का MIME प्रकार लौटाता है, जो (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। केवल- पढ़ने योग्य String.

**रिटर्न्स:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


ऑडियो डेटा की प्रति लौटाता है। बड़ी मात्रा में डेटा के मामले में \#getStream.getStream मेथड का उपयोग करने पर विचार करें ताकि वीडियो डेटा को मेमोरी में अनावश्यक रूप से लोड करने या OutOfMemoryException से बचा जा सके। केवल- पढ़ने योग्य byte[].

**रिटर्न्स:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


पढ़ने के लिए Stream स्ट्रीम लौटाता है। 'using' का प्रयोग करें या उपयोग के बाद स्ट्रीम को बंद करें।

**रिटर्न्स:**
java.io.InputStream - पढ़ने के लिए स्ट्रीम।