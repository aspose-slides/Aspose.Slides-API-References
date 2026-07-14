---
title: Audio
second_title: Aspose.Slides के लिए Android द्वारा Java API Reference
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

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getContentType()](#getContentType--) | ऑडियो का MIME प्रकार लौटाता है, जिसे (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। |
| [setContentType(String value)](#setContentType-java.lang.String-) | ऑडियो का MIME प्रकार लौटाता है, जिसे (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। |
| [getBinaryData()](#getBinaryData--) | ऑडियो के डेटा की प्रतिलिपि लौटाता है। |
| [getStream()](#getStream--) | पढ़ने के लिए Stream स्ट्रीम लौटाता है। |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

ऑडियो का MIME प्रकार लौटाता है, जिसे (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। केवल-पढ़ने योग्य String.

**रिटर्न:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

ऑडियो का MIME प्रकार लौटाता है, जिसे (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। केवल-पढ़ने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

ऑडियो के डेटा की प्रतिलिपि लौटाता है। बड़े डेटा की मात्रा के मामले में \#getStream.getStream मेथड के उपयोग पर विचार करें ताकि ऑडियो के डेटा को मेमोरी में अनावश्यक रूप से लोड करने या OutOfMemoryException होने से बचा जा सके। केवल-पढ़ने योग्य byte[]।

**रिटर्न:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

पढ़ने के लिए Stream स्ट्रीम लौटाता है। उपयोग के बाद 'using' का प्रयोग करें या स्ट्रीम को बंद करें।

**रिटर्न:**  
java.io.InputStream - पढ़ने के लिए Stream.