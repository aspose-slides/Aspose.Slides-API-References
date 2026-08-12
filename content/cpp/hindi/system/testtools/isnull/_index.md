---
title: IsNull()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि विशिष्ट मान null है। अंकगणितीय और enum प्रकारों के लिए संस्करण।
type: docs
weight: 1
url: /hi/system/testtools/isnull/
---
## TestTools::IsNull(T) method


जाँचता है कि विशिष्ट मान null है। [Version](../../version/) अंकगणितीय और enum प्रकारों के लिए।

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जांचे जा रहे मान का प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T | null के लिए जाँचने वाला मान। |

### वापसी मान

हमेशा false लौटाता है।

## TestTools::IsNull(const T\&) method


जाँचता है कि विशिष्ट मान null है। [Version](../../version/) गैर-अंकगणितीय और गैर-enum मान प्रकारों के लिए।

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जांचे जा रहे मान का प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | null के लिए जाँचने वाला मान। |

### वापसी मान

यदि वस्तु को nullptr के साथ true के रूप में तुलना किया जाता है तो true, अन्यथा false।

## TestTools::IsNull(const SharedPtr\<T\>\&) method


जाँचता है कि विशिष्ट मान null है। [Version](../../version/) गैर-अंकगणितीय मान प्रकारों के लिए।

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जांचे जा रहे मान का प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | null के लिए जाँचने वाला मान। |

### वापसी मान

यदि वस्तु को nullptr के साथ true के रूप में तुलना किया जाता है तो true, अन्यथा false।

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) method


जाँचता है कि विशिष्ट मान null है। [Version](../../version/) कुंजी-मूल्य जोड़ों के लिए।

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| V | मान प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | जोड़ी ऑब्जेक्ट। |

### वापसी मान

यदि जोड़ी को null माना जाता है तो true, अन्यथा false।

## TestTools::IsNull(const System::String\&) method


जाँचता है कि स्ट्रिंग null है।

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | जाँचने के लिए [String](../../string/)। |

### वापसी मान

यदि स्ट्रिंग को null माना जाता है तो true, अन्यथा false।

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)