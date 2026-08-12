---
title: operator!=()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: 
type: docs
weight: 2055
url: /hi/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) फ़ंक्शन




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) फ़ंक्शन




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) फ़ंक्शन




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) फ़ंक्शन


निर्धारित करता है कि निर्दिष्ट [Nullable](../nullable/) वस्तु null के बराबर न होने वाला मान दर्शाती है।

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | std::nullptr_t | परीक्षण हेतु एक स्थिर संदर्भ [Nullable](../nullable/) वस्तु का |

### रिटर्न मान

यदि निर्दिष्ट वस्तु non-null मान दर्शाती है तो true, अन्यथा false

## System::operator!=(const T1\&, const Nullable\<T2\>\&) फ़ंक्शन


निर्धारित करता है कि इन मानों पर [operator!=()](./) लागू करके निर्दिष्ट [Nullable](../nullable/) वस्तु द्वारा दर्शाए गए मान के बराबर नहीं है।

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | पहले तुलना मान का प्रकार |
| T2 | [Nullable](../nullable/) वस्तु का मौलिक प्रकार जो दूसरे तुलना मान को दर्शाता है |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| some | const T1\& | पहले तुलना मान के रूप में उपयोग करने के लिए मान का एक स्थिर संदर्भ |
| other | const [Nullable](../nullable/)\<T2\>\& | दूसरे तुलना मान के रूप में उपयोग करने के लिए प्रदर्शित मान वाला [Nullable](../nullable/) वस्तु का एक स्थिर संदर्भ |

### रिटर्न मान

यदि तुलना मान बराबर नहीं हैं तो true, अन्यथा false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) फ़ंक्शन


दो स्मार्ट पॉइंटर्स की असमान तुलना करता है।

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | पहले पॉइंटर का pointee प्रकार। |
| Y | दूसरे पॉइंटर का pointee प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | तुलना हेतु पहला पॉइंटर। |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | तुलना हेतु दूसरा पॉइंटर। |

### रिटर्न मान

यदि पॉइंटर मेल खाते हैं तो false, अन्यथा true।

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) फ़ंक्शन


जांचता है कि स्मार्ट पॉइंटर null नहीं है।

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | पॉइंटर का pointee प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | जाँचने हेतु पॉइंटर। |

### रिटर्न मान

यदि पॉइंटर null है तो false, अन्यथा true।

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) फ़ंक्शन


जांचता है कि स्मार्ट पॉइंटर null नहीं है।

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | पॉइंटर का pointee प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | std::nullptr_t | जाँचने हेतु पॉइंटर। |

### रिटर्न मान

यदि पॉइंटर null है तो false, अन्यथा true।

## System::operator!=(const SmartPtr\<X\>\&, const Y *) फ़ंक्शन


स्मार्ट पॉइंटर और साधारण (C) पॉइंटर की असमानता तुलना।

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | स्मार्ट पॉइंटर का प्रकार। |
| Y | साधारण पॉइंटर का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | बाईं ओर तुलना हेतु स्मार्ट पॉइंटर। |
| y | const Y * | दाईं ओर तुलना हेतु पॉइंटर। |

### रिटर्न मान

यदि पॉइंटर मेल खाते हैं तो false, अन्यथा true।

## System::operator!=(const X *, const SmartPtr\<Y\>\&) फ़ंक्शन


स्मार्ट पॉइंटर और साधारण (C) पॉइंटर की समानता तुलना।

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | साधारण पॉइंटर का प्रकार। |
| Y | स्मार्ट पॉइंटर का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const X * | दाईं ओर तुलना हेतु पॉइंटर। |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | बाईं ओर तुलना हेतु स्मार्ट पॉइंटर। |

### रिटर्न मान

यदि पॉइंटर मेल खाते हैं तो false, अन्यथा true।

## System::operator!=(Chars\&, const String\&) फ़ंक्शन


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Chars | [String](../string/) literal type. |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | Chars\& | [String](../string/) लिटरल तुलना के लिए। |
| right | const [String](../string/)\& | तुलना हेतु [String](../string/)। |

### रिटर्न मान

यदि स्ट्रिंग्स मेल खाती हैं तो false, अन्यथा true।

## System::operator!=(T\&, const String\&) फ़ंक्शन


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [String](../string/) pointer type. |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | T\& | तुलना हेतु [String](../string/) पॉइंटर। |
| right | const [String](../string/)\& | तुलना हेतु [String](../string/)। |

### रिटर्न मान

यदि स्ट्रिंग्स मेल खाती हैं तो false, अन्यथा true।

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) फ़ंक्शन


[Object](../object/) और स्ट्रिंग तुलना।

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | तुलना हेतु [Object](../object/) को स्ट्रिंग में बदलकर। |
| right | const [String](../string/)\& | तुलना हेतु [String](../string/)। |

### रिटर्न मान

यदि वस्तु का स्ट्रिंग प्रतिनिधित्व स्ट्रिंग के बराबर है तो false, अन्यथा true।

## System::operator!=(std::nullptr_t, const String\&) फ़ंक्शन


जांचता है कि स्ट्रिंग null है या नहीं।

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | std::nullptr_t | जाँचने हेतु [String](../string/)। |

### रिटर्न मान

यदि स्ट्रिंग null है तो false, अन्यथा true।

## System::operator!=(std::nullptr_t, TimeSpan) फ़ंक्शन




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) फ़ंक्शन


निर्धारित करता है कि वर्तमान और निर्दिष्ट वस्तुओं द्वारा प्रतिनिधित्व किए गए URI असमान हैं या नहीं।

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | तुलना हेतु पहला [Uri](../uri/) वस्तु |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | तुलना हेतु दूसरा [Uri](../uri/) वस्तु |

### रिटर्न मान

यदि URI असमान हैं तो true, अन्यथा false

## संबंधित देखें

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)