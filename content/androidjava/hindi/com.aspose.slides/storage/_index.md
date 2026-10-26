---
title: Storage
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: अस्थायी डेटा भंडारण का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/storage/
---
**विरासत:**
java.lang.Object
```
public final class Storage
```

[WebDocument](../../com.aspose.slides/webdocument) के लिए एक अस्थायी डेटा भंडारण का प्रतिनिधित्व करता है।

## निर्माता

| निर्माणकर्ता | विवरण |
| --- | --- |
| [Storage()](#Storage--) |  |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | मान को भंडारण में रखता है। |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | भंडारण से डेटा प्राप्त करता है। |
| [containsKey(String key)](#containsKey-java.lang.String-) | निर्धारित करता है कि भंडारण में निर्दिष्ट कुंजी वाला तत्व है या नहीं। |
### Storage() {#Storage--}
```
public Storage()
```

### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

मान को भंडारण में रखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मान के लिये कुंजी। |
| value | TValue | मान। |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

भंडारण से डेटा प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मान की कुंजी। |

**रिटर्न:**
TValue - डेटा मान यदि यह डेटा संग्रह में प्रस्तुत है, अन्यथा null।

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

निर्धारित करता है कि भंडारण में निर्दिष्ट कुंजी वाला तत्व है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मान की कुंजी। |

**रिटर्न:**
boolean - सत्य यदि भंडारण में निर्दिष्ट कुंजी वाला तत्व है, अन्यथा असत्य।