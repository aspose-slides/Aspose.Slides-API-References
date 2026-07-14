---
title: Size
second_title: Aspose.Slides for Android, Java API रेफ़रेंस के माध्यम से
description: किसी मनमाने इकाई में चौड़ाई और ऊँचाई आयामों का वर्णन करने वाली क्लास।
type: docs
url: /hi/com.aspose.slides.android/size/
---
**विरासत:**
java.lang.Object
```
public class Size
```

किसी मनमाने इकाई में चौड़ाई और ऊँचाई आयामों का वर्णन करने के लिए क्लास।

## कन्स्ट्रक्टर

| निर्माता | विवरण |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | नया Size इंस्टेंस बनाएं। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | आकार की चौड़ाई प्राप्त करें। |
| [getHeight()](#getHeight--) | आकार की ऊँचाई प्राप्त करें। |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचें कि यह आकार किसी अन्य आकार के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | आकार को स्ट्रिंग के रूप में "WxH" प्रारूप में लौटाएं। |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

नया Size इंस्टेंस बनाएं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | आकार की चौड़ाई |
| height | int | आकार की ऊँचाई |

### getWidth() {#getWidth--}
```
public int getWidth()
```

आकार की चौड़ाई प्राप्त करें।

**रिटर्न:**
int - width

### getHeight() {#getHeight--}
```
public int getHeight()
```

आकार की ऊँचाई प्राप्त करें।

**रिटर्न:**
int - height

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

जाँचें कि यह आकार किसी अन्य आकार के बराबर है या नहीं।

दो आकार तभी बराबर होते हैं जब उनकी चौड़ाइयाँ और ऊँचाइयाँ दोनों बराबर हों।

एक आकार वस्तु कभी भी किसी अन्य प्रकार की वस्तु के बराबर नहीं होती।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**रिटर्न:**
boolean -  true यदि वस्तुएँ समान थीं,  false अन्यथा

### hashCode() {#hashCode--}
```
public int hashCode()
```


**रिटर्न:**
int

### toString() {#toString--}
```
public String toString()
```

आकार को स्ट्रिंग के रूप में "WxH" प्रारूप में लौटाएं।

**रिटर्न:**
java.lang.String - आकार का स्ट्रिंग प्रतिनिधित्व