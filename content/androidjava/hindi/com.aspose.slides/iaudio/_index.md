---
title: IAudio
second_title: Aspose.Slides एंड्रॉइड के लिए जाव़ा API संदर्भ के माध्यम से
description: एक एम्बेडेड ऑडियो फ़ाइल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iaudio/
---```
public interface IAudio
```

एक एम्बेडेड ऑडियो फ़ाइल का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getContentType()](#getContentType--) | ऑडियो का MIME प्रकार लौटाता है, (\#getBinaryData.getBinaryData) में एन्कोडेड। |
| [getBinaryData()](#getBinaryData--) | ऑडियो डेटा की कॉपी लौटाता है। |
| [getStream()](#getStream--) | पढ़ने के लिए Stream स्ट्रिम लौटाता है। |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

ऑडियो का MIME प्रकार लौटाता है, (\#getBinaryData.getBinaryData) में एन्कोडेड। केवल पढ़ने योग्य String.

**वापसी:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

ऑडियो डेटा की कॉपी लौटाता है। बड़ी मात्रा में डेटा होने पर \#getStream.getStream मेथड का उपयोग करने पर विचार करें ताकि ऑडियो डेटा को मेमोरी में अनावश्यक रूप से लोड करने या OutOfMemoryException होने से बचा जा सके। केवल पढ़ने योग्य byte[]।

**वापसी:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

पढ़ने के लिए Stream स्ट्रिम लौटाता है। उपयोग करने के बाद 'using' का उपयोग करें या स्ट्रिम को बंद करें।

**वापसी:**
java.io.InputStream - पढ़ने के लिए स्ट्रिम।