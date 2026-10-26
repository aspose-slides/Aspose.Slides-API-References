---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /hi/com.aspose.slides/ivideo/
---```
public interface IVideo
```

एक प्रस्तुति में सम्मिलित वीडियो का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getContentType()](#getContentType--) | एक वीडियो का MIME प्रकार लौटाता है, जो (\#getBinaryData.getBinaryData) में एनकोड किया गया है। |
| [getBinaryData()](#getBinaryData--) | ऑडियो डेटा की प्रति लौटाता है। |
| [getStream()](#getStream--) | पढ़ने के लिए Stream स्ट्रीम लौटाता है। |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


एक वीडियो का MIME प्रकार लौटाता है, जो (\#getBinaryData.getBinaryData) में एनकोड किया गया है। केवल- पढ़ने योग्य String.

**वापसी:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


ऑडियो डेटा की प्रति लौटाता है। बड़े डेटा की मात्रा के मामले में \#getStream.getStream विधि का उपयोग करने पर विचार करें ताकि वीडियो डेटा को मेमोरी में अनावश्यक रूप से लोड करने या OutOfMemoryException से बचा जा सके। केवल- पढ़ने योग्य byte[]।

**वापसी:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


पढ़ने के लिए Stream स्ट्रीम लौटाता है। उपयोग के बाद 'using' का प्रयोग करें या स्ट्रीम को बंद करें।

**वापसी:**
java.io.InputStream - पढ़ने के लिए स्ट्रीम।