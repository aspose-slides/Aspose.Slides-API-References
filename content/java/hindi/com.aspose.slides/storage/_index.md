---
title: Storage
second_title: Aspose.Slides के लिए Java API संदर्भ
description: अस्थायी डेटा भंडारण का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/storage/
---
**विरासत:**
java.lang.Object
```
public final class Storage
```

[WebDocument](../../com.aspose.slides/webdocument) के लिए अस्थायी डेटा भंडारण का प्रतिनिधित्व करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Storage()](#Storage--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | मूल्य को भंडारण में रखता है। |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | भंडारण से डेटा प्राप्त करता है। |
| [containsKey(String key)](#containsKey-java.lang.String-) | निर्धारित करता है कि क्या भंडारण में निर्दिष्ट कुंजी वाला तत्व मौजूद है। |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


भंडारण में मूल्य को रखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मूल्य की कुंजी। |
| value | TValue | मूल्य। |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


भंडारण से डेटा प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मूल्य की कुंजी। |

**वापसी:**
TValue - डेटा मान यदि डेटा संग्रह में मौजूद है, अन्यथा null।

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


निर्धारित करता है कि क्या भंडारण में निर्दिष्ट कुंजी वाला तत्व मौजूद है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | |
| key | java.lang.String | मूल्य की कुंजी। |

**वापसी:**
boolean - यदि भंडारण में निर्दिष्ट कुंजी वाला तत्व है तो true, अन्यथा false।