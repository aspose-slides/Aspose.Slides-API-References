---
title: SizeF
second_title: Aspose.Slides Android के लिए, Java API संदर्भ के माध्यम से
description: कुछ मनमानी इकाई में फ्लोटिंग-पॉइंट मानों के साथ चौड़ाई और ऊँचाई आयामों का वर्णन करने के लिये क्लास।
type: docs
url: /hi/com.aspose.slides.android/sizef/
---
**विरासत:**
java.lang.Object
```
public class SizeF
```

कुछ मनमाने इकाई में फ्लोटिंग-पॉइंट मानों के साथ चौड़ाई और ऊँचाई आयामों का वर्णन करने हेतु क्लास।
## निर्माता

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | एक नया SizeF इंस्टेंस बनाएं। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | आकार की चौड़ाई प्राप्त करें। |
| [getHeight()](#getHeight--) | आकार की ऊँचाई प्राप्त करें। |
| [equals(Object obj)](#equals-java.lang.Object-) | जांचें कि यह आकार किसी अन्य आकार के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | आकार को स्ट्रिंग के रूप में लौटाएँ जिसमें स्वरूप "WxH" हो। |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


एक नया SizeF इंस्टेंस बनाएं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | आकार की चौड़ाई |
| height | float | आकार की ऊँचाई |

### getWidth() {#getWidth--}
```
public float getWidth()
```


आकार की चौड़ाई प्राप्त करें।

**रिटर्न:**
float - चौड़ाई
### getHeight() {#getHeight--}
```
public float getHeight()
```


आकार की ऊँचाई प्राप्त करें।

**रिटर्न:**
float - ऊँचाई
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जांचें कि यह आकार किसी अन्य आकार के बराबर है या नहीं।

दो आकार तभी समान होते हैं जब उनकी चौड़ाइयाँ और ऊँचाइयाँ दोनों समान हों।

इस उद्देश्य के लिए, चौड़ाई/ऊँचाई के फ्लोट मानों को तभी समान माना जाता है जब मेथड Float\#floatToIntBits(float).floatToIntBits(float) प्रत्येक पर लागू होने पर समान  int  मान लौटाए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**रिटर्न:**
boolean -  true  यदि ऑब्जेक्ट समान थे,  false  अन्यथा
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


आकार को स्ट्रिंग के रूप में लौटाएँ जिसमें स्वरूप "WxH" हो।

**रिटर्न:**
java.lang.String - आकार का स्ट्रिंग प्रतिनिधित्व