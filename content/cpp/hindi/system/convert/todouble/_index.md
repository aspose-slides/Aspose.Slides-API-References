---
title: ToDouble()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट boolean मान को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।
type: docs
weight: 222
url: /hi/system/convert/todouble/
---
## Convert::ToDouble(bool) विधि

निर्दिष्ट boolean मान को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```
## Convert::ToDouble(uint8_t) विधि

निर्दिष्ट 8-बिट unsigned integer को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```
## Convert::ToDouble(int8_t) विधि

निर्दिष्ट 8-बिट signed integer को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```
## Convert::ToDouble(uint16_t) विधि

निर्दिष्ट 16-बिट unsigned integer को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```
## Convert::ToDouble(int16_t) विधि

निर्दिष्ट 16-बिट signed integer को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```
## Convert::ToDouble(uint32_t) विधि

निर्दिष्ट 32-बिट unsigned integer को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```
## Convert::ToDouble(int32_t) विधि

निर्दिष्ट 32-बिट signed integer को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```
## Convert::ToDouble(uint64_t) विधि

निर्दिष्ट 64-बिट unsigned integer को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```
## Convert::ToDouble(int64_t) विधि

निर्दिष्ट 64-बिट signed integer को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```
## Convert::ToDouble(float) विधि

निर्दिष्ट single-precision संख्या को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(float value)
```
## Convert::ToDouble(double) विधि

निर्दिष्ट double संख्या लौटाता है।

```cpp
static constexpr double System::Convert::ToDouble(double value)
```
## Convert::ToDouble(const Decimal\&) विधि

निर्दिष्ट दशमलव संख्या को समतुल्य double-precision फ़्लोटिंग पॉइंट संख्या में परिवर्तित करता है।

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```
## Convert::ToDouble(char_t) विधि

रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है।

```cpp
static double System::Convert::ToDouble(char_t value)
```
## Convert::ToDouble(DateTime) विधि

रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है।

```cpp
static double System::Convert::ToDouble(DateTime value)
```
## Convert::ToDouble(std::nullptr_t) विधि

निर्दिष्ट null-string को समतुल्य double-precision फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Return Value

शून्य।

## Convert::ToDouble(const char_t *) विधि

निर्दिष्ट c-string जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समतुल्य double-precision फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | परिवर्तित करने के लिए c-string |

### Return Value

निर्दिष्ट c-string द्वारा प्रतिनिधित्व किए गए संख्या के बराबर double-precision फ़्लोटिंग पॉइंट मान

## Convert::ToDouble(const String\&) विधि

निर्दिष्ट string जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समतुल्य double-precision फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए string |

### Return Value

निर्दिष्ट string द्वारा प्रतिनिधित्व किए गए संख्या के बराबर double-precision फ़्लोटिंग पॉइंट मान

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) विधि

प्रदान किए गए फ़ॉर्मेटिंग जानकारी का उपयोग करके निर्दिष्ट string जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समतुल्य double-precision फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए string |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | वह ऑब्जेक्ट का पॉइंटर जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी है |

### Return Value

निर्दिष्ट string द्वारा प्रतिनिधित्व किए गए संख्या के बराबर double-precision फ़्लोटिंग पॉइंट मान

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) विधि




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) विधि 




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) विधि

प्रदान किए गए फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके निर्दिष्ट string जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समतुल्य double-precision फ़्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए string |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली निर्दिष्ट करता है |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | वह ऑब्जेक्ट का पॉइंटर जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी है |

### Return Value

निर्दिष्ट string द्वारा प्रतिनिधित्व किए गए संख्या के बराबर double-precision फ़्लोटिंग पॉइंट मान

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) विधि 




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि 




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) विधि 




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) विधि

निर्दिष्ट बॉक्स्ड मान को double-precision फ़्लोटिंग पॉइंट मान में परिवर्तित करता है। यदि बॉक्स्ड मान का प्रकार [String](../../string/) है, तो रूपांतरण के दौरान निर्दिष्ट स्ट्रिंग फ़ॉर्मेट का उपयोग किया जाता है।

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | परिवर्तित करने के लिए मान को बॉक्स करने वाले ऑब्जेक्ट का shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | यदि बॉक्स्ड मान का प्रकार [String](../../string/) है तो उपयोग किया जाने वाला स्ट्रिंग फ़ॉर्मेट |

### Return Value

निर्दिष्ट बॉक्स्ड मान के बराबर double-precision फ़्लोटिंग पॉइंट मान

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)