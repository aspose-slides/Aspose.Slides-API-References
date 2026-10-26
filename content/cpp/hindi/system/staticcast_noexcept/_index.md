---
title: StaticCast_noexcept()
second_title: Aspose.Slides for C++ API संदर्भ
description: SmartPtr ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।
type: docs
weight: 2549
url: /hi/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) फ़ंक्शन

[SmartPtr](../smartptr/) ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य पॉइनी प्रकार। |
| TFrom | स्रोत पॉइनी प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | स्रोत पॉइंटर। |

### रिटर्न वैल्यू

यदि कास्ट अनुमति है तो कास्ट परिणाम, अन्यथा nullptr।

डिप्रिकेटेड
:   पीछे की संगतता के लिए रखा गया है। इसके बजाय AsCast का उपयोग करें।

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) फ़ंक्शन

[WeakPtr](../weakptr/) ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य पॉइनी प्रकार। |
| TFrom | स्रोत पॉइनी प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | स्रोत पॉइंटर। |

### रिटर्न वैल्यू

यदि कास्ट अनुमति है तो कास्ट परिणाम, अन्यथा nullptr।

डिप्रिकेटेड
:   पीछे की संगतता के लिए रखा गया है। इसके बजाय AsCast का उपयोग करें।

## System::StaticCast_noexcept(const TFrom\&) फ़ंक्शन

Exception ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
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

यदि कास्ट अनुमति है तो कास्ट परिणाम, अन्यथा nullptr।

डिप्रिकेटेड
:   पीछे की संगतता के लिए रखा गया है। इसके बजाय AsCast का उपयोग करें।

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) फ़ंक्शन

Objects को Exception ऑब्जेक्ट्स में स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य Exception प्रकार। |
| TFrom | [Object](../object/) टाइप। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | स्रोत पॉइंटर। |

### रिटर्न वैल्यू

यदि कास्ट अनुमति है तो कास्ट परिणाम, अन्यथा nullptr।

डिप्रिकेटेड
:   पीछे की संगतता के लिए रखा गया है। इसके बजाय AsCast का उपयोग करें।

## देखें

* क्लास [SmartPtr](../smartptr/)
* क्लास [WeakPtr](../weakptr/)
* क्लास [Object](../object/)
* स्ट्रक्ट [IsExceptionWrapper](../isexceptionwrapper/)
* स्ट्रक्ट [CastResult](../castresult/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)