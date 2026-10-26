---
title: Equals()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 14
url: /hi/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) मेथड




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) मेथड


C# [Object.Equals](../../object/equals/) कॉलों के लिए प्रतिस्थापन, जो C++ में किसी भी प्रकार के लिए काम करता है। स्मार्ट पॉइंटर प्रकारों के लिए ओवरलोड।

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | पहला ऑब्जेक्ट प्रकार। |
| T2 | दूसरा ऑब्जेक्ट प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | पहला ऑब्जेक्ट। |
| another | const T2\& | दूसरा ऑब्जेक्ट। |

### रिटर्न मान

यदि ऑब्जेक्ट समान माने जाते हैं तो true, अन्यथा false।

## ObjectExt::Equals(T, const T2\&) मेथड


C# [Object.Equals](../../object/equals/) कॉलों के लिए प्रतिस्थापन, जो C++ में किसी भी प्रकार के लिए काम करता है। स्ट्रक्चर प्रकारों के लिए ओवरलोड।

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | पहला ऑब्जेक्ट प्रकार। |
| T2 | दूसरा ऑब्जेक्ट प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T | पहला ऑब्जेक्ट। |
| another | const T2\& | दूसरा ऑब्जेक्ट। |

### रिटर्न मान

यदि ऑब्जेक्ट समान माने जाते हैं तो true, अन्यथा false।

## ObjectExt::Equals(const T\&, const T2\&) मेथड


C# [Object.Equals](../../object/equals/) कॉलों के लिए प्रतिस्थापन, जो C++ में किसी भी प्रकार के लिए काम करता है। स्केलेर प्रकारों के लिए ओवरलोड।

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | पहला ऑब्जेक्ट प्रकार। |
| T2 | दूसरा ऑब्जेक्ट प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | पहला ऑब्जेक्ट। |
| another | const T2\& | दूसरा ऑब्जेक्ट। |

### रिटर्न मान

यदि ऑब्जेक्ट समान माने जाते हैं तो true, अन्यथा false।

## ObjectExt::Equals(const char_t(&), String) मेथड


C# [Object.Equals](../../object/equals/) कॉलों के लिए प्रतिस्थापन, जो C++ में किसी भी प्रकार के लिए काम करता है। स्ट्रिंग लिटरल के साथ स्ट्रिंग तुलना के लिए ओवरलोड।

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| N | [String](../../string/) लिटरल आकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) लिटरल। |
| another | [String](../../string/) | [String](../../string/)। |

### रिटर्न मान

यदि स्ट्रिंग मेल खाती हैं तो true, अन्यथा false।

## ObjectExt::Equals(const float\&, const float\&) मेथड


C# शैली के फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है।

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const **float**\& | बाएँ पक्ष का फ़्लोटिंग पॉइंट मान। |
| another | const **float**\& | दाएँ पक्ष का फ़्लोटिंग पॉइंट मान। |

### रिटर्न मान

यदि **obj** और **another** दोनों NaN हों या समान हों तो true, अन्यथा false।

## ObjectExt::Equals(const double\&, const double\&) मेथड


C# शैली के फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है।

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const **double**\& | बाएँ पक्ष का फ़्लोटिंग पॉइंट मान। |
| another | const **double**\& | दाएँ पक्ष का फ़्लोटिंग पॉइंट मान। |

### रिटर्न मान

यदि **obj** और **another** दोनों NaN हों या समान हों तो true, अन्यथा false।

## सम्बंधित

* क्लास [ObjectExt](../)
* क्लास [String](../../string/)
* स्ट्रक्ट [IsExceptionWrapper](../../isexceptionwrapper/)
* स्ट्रक्ट [IsSmartPtr](../../issmartptr/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)