---
title: Audio
second_title: Aspose.Slides for Java API संदर्भ
description: एक एम्बेडेड ऑडियो फ़ाइल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/audio/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

एक एम्बेडेड ऑडियो फ़ाइल का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getContentType()](#getContentType--) | ऑडियो का MIME प्रकार लौटाता है, जिसे (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। |
| [setContentType(String value)](#setContentType-java.lang.String-) | ऑडियो का MIME प्रकार लौटाता है, जिसे (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। |
| [getBinaryData()](#getBinaryData--) | ऑडियो के डेटा की प्रति लौटाता है। |
| [getStream()](#getStream--) | पढ़ने के लिए Stream स्ट्रीम लौटाता है। |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

ऑडियो का MIME प्रकार लौटाता है, जिसे (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। पढ़ने-के-लिए-केवल String।

**वापसी:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

ऑडियो का MIME प्रकार लौटाता है, जिसे (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। पढ़ने-के-लिए-केवल String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

ऑडियो के डेटा की प्रति लौटाता है। बड़ी मात्रा में डेटा के मामले में \#getStream.getStream मेथड का उपयोग करने पर विचार करें ताकि ऑडियो के डेटा को मेमोरी में अनावश्यक रूप से लोड करने या OutOfMemoryException से बचा जा सके। पढ़ने-के-लिए-केवल byte[]।

**वापसी:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

पढ़ने के लिए Stream स्ट्रीम लौटाता है। 'using' का उपयोग करें या उपयोग के बाद स्ट्रीम को बंद करें।

**वापसी:**
java.io.InputStream - पढ़ने के लिए स्ट्रीम।