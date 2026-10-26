---
title: Zip64Mode
second_title: Aspose.Slides for Java API संदर्भ
description: OpenXML फ़ाइल के लिए ZIP64 फ़ॉर्मेट एक्सटेंशन के उपयोग का समय निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/zip64mode/
---
**वंशानुक्रम:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

OpenXML फ़ाइल के लिए ZIP64 फ़ॉर्मेट एक्सटेंशन के उपयोग का समय निर्दिष्ट करता है।

--------------------

OpenXML फ़ाइल एक ZIP-आर्काइव है जिसमें फ़ाइल के अनकम्प्रेस्ड आकार, कम्प्रेस्ड आकार और आर्काइव के कुल आकार पर 4 GB (2^32 बाइट्स) की सीमा होती है, साथ ही आर्काइव में 65,535 (2^16-1) फ़ाइलों की सीमा होती है। ZIP64 फ़ॉर्मेट एक्सटेंशन इन सीमाओं को 2^64 तक बढ़ा देते हैं।

## फ़ील्ड

| Field | Description |
| --- | --- |
| [Never](#Never) | ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग न करें। |
| [IfNecessary](#IfNecessary) | यदि आवश्यक हो तो ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग करें। |
| [Always](#Always) | सदैव ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग करें। |
### Never {#Never}
```
public static final int Never
```

ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग न करें।

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

यदि आवश्यक हो तो ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग करें।

### Always {#Always}
```
public static final int Always
```

सदैव ZIP64 फ़ॉर्मेट एक्सटेंशन का उपयोग करें।