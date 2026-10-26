---
title: DynamicCast()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: Exception ऑब्जेक्ट्स पर डायनेमिक कास्ट निष्पादित करता है।
type: docs
weight: 2536
url: /hi/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) फ़ंक्शन


Exception ऑब्जेक्ट्स पर डायनेमिक कास्ट निष्पादित करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य Exception प्रकार। |
| TFrom | स्रोत Exception प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const TFrom\& | स्रोत पॉइंटर। |

### रिटर्न वैल्यू

यदि कास्ट की अनुमति है तो कास्ट परिणाम।

डिप्रिकेटेड
:   पिछले संस्करणों के साथ संगतता बनाए रखने के लिए छोड़ दिया गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::DynamicCast(SmartPtr\<TFrom\> const\&) फ़ंक्शन


[SmartPtr](../smartptr/) ऑब्जेक्ट्स पर डायनेमिक कास्ट निष्पादित करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य पॉइंटी टाइप। |
| TFrom | स्रोत पॉइंटी टाइप। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | स्रोत पॉइंटर। |

### रिटर्न वैल्यू

यदि कास्ट की अनुमति है तो कास्ट परिणाम।

डिप्रिकेटेड
:   पिछले संस्करणों के साथ संगतता बनाए रखने के लिए छोड़ दिया गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::DynamicCast(SmartPtr\<TFrom\>) फ़ंक्शन


कास्ट के द्वारा बॉक्स्ड enum को अनबॉक्स करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य enum प्रकार। |
| TFrom | स्रोत पॉइंटी टाइप। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | डेटा अनबॉक्स करने के लिए ऑब्जेक्ट का पॉइंटर। |

### रिटर्न वैल्यू

अनबॉक्स किया गया enum मान।

डिप्रिकेटेड
:   पिछले संस्करणों के साथ संगतता बनाए रखने के लिए छोड़ दिया गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::DynamicCast(std::nullptr_t) फ़ंक्शन


null ऑब्जेक्ट्स पर डायनेमिक कास्ट निष्पादित करता है।

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य पॉइंटी टाइप। |

### रिटर्न वैल्यू

nullptr।

डिप्रिकेटेड
:   पिछले संस्करणों के साथ संगतता बनाए रखने के लिए छोड़ दिया गया है। इसके अलावा ExplicitCast का उपयोग करें।

## System::DynamicCast(TFrom\&) फ़ंक्शन


नॉन-पॉइंटर ऑब्जेक्ट्स पर डायनेमिक कास्ट निष्पादित करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य प्रकार। |
| TFrom | स्रोत प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | TFrom\& | स्रोत ऑब्जेक्ट। |

### रिटर्न वैल्यू

कास्ट परिणाम।

डिप्रिकेटेड
:   पिछले संस्करणों के साथ संगतता बनाए रखने के लिए छोड़ दिया गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::DynamicCast(SmartPtr\<TFrom\>) फ़ंक्शन


Objects को Exception ऑब्जेक्ट्स में डायनेमिक कास्ट निष्पादित करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य Exception प्रकार। |
| TFrom | [Object](../object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | स्रोत पॉइंटर। |

### रिटर्न वैल्यू

यदि कास्ट की अनुमति है तो कास्ट परिणाम।

डिप्रिकेटेड
:   पिछले संस्करणों के साथ संगतता बनाए रखने के लिए छोड़ दिया गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::DynamicCast(TFrom) फ़ंक्शन


IntPtr से पॉइंटर में डायनेमिक कास्ट निष्पादित करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य प्रकार। |
| TFrom | स्रोत प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | TFrom | स्रोत IntPtr मान। |

### रिटर्न वैल्यू

कास्ट परिणाम।

डिप्रिकेटेड
:   पिछले संस्करणों के साथ संगतता बनाए रखने के लिए छोड़ दिया गया है। इसके बजाय ExplicitCast का उपयोग करें।

## देखें भी

* क्लास [SmartPtr](../smartptr/)
* क्लास [Object](../object/)
* संरचना [IsExceptionWrapper](../isexceptionwrapper/)
* संरचना [CastResult](../castresult/)
* संरचना [IsSmartPtr](../issmartptr/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)