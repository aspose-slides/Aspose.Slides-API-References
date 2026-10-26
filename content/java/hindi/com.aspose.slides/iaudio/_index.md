---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /hi/com.aspose.slides/iaudio/
---```
public interface IAudio
```

एक एम्बेडेड ऑडियो फ़ाइल का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getContentType()](#getContentType--) | ऑडियो का MIME टाइप लौटाता है, जो (\#getBinaryData.getBinaryData) में एन्कोडेड है। |
| [getBinaryData()](#getBinaryData--) | ऑडियो डेटा की प्रतिलिपि लौटाता है। |
| [getStream()](#getStream--) | पढ़ने के लिए Stream स्ट्रीम लौटाता है। |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

ऑडियो का MIME टाइप लौटाता है, जो (\#getBinaryData.getBinaryData) में एन्कोडेड है। केवल-पढ़ने योग्य String.

**वापसी:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

ऑडियो डेटा की प्रतिलिपि लौटाता है। बड़ी मात्रा में डेटा के मामले में \#getStream.getStream मेथड का उपयोग करने पर विचार करें ताकि ऑडियो डेटा को मेमोरी में अनावश्यक रूप से लोड करने या OutOfMemoryException से बचा जा सके। केवल-पढ़ने योग्य byte[].

**वापसी:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

पढ़ने के लिए Stream स्ट्रीम लौटाता है। उपयोग के बाद 'using' का प्रयोग करें या स्ट्रीम बंद करें।

**वापसी:**
java.io.InputStream - पढ़ने के लिए स्ट्रीम।