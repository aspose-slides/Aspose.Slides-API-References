---
title: Zip64Mode
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस द्वारा
description: OpenXML फ़ाइल के लिए ZIP64 फ़ॉर्मेट एक्सटेंशन कब उपयोग करना है, यह निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/zip64mode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

OpenXML फ़ाइल के लिए ZIP64 फ़ॉर्मेट एक्सटेंशन कब उपयोग करना है, यह निर्दिष्ट करता है।

--------------------

OpenXML फ़ाइल एक ZIP-आर्काइव है जिसमें फ़ाइल के अनकम्प्रेस्ड आकार, कम्प्रेस्ड आकार और आर्काइव के कुल आकार पर 4 GB (2^32 बाइट) की सीमा है, साथ ही आर्काइव में 65 535 (2^16-1) फ़ाइलों की सीमा है। ZIP64 फ़ॉर्मेट एक्सटेंशन इन सीमाओं को 2^64 तक बढ़ा देते हैं।

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Never](#Never) | ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग न करें। |
| [IfNecessary](#IfNecessary) | यदि आवश्यक हो तो ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग करें। |
| [Always](#Always) | हमेशा ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग करें। |
### कभी नहीं {#Never}
```
public static final int Never
```


ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग न करें।

### यदि आवश्यक {#IfNecessary}
```
public static final int IfNecessary
```


यदि आवश्यक हो तो ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग करें।

### हमेशा {#Always}
```
public static final int Always
```


हमेशा ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग करें।