---
title: DynamicCast_noexcept()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: पुराने अप्रचलित कास्ट। भविष्य के संस्करणों में हटा दिया जाएगा।
type: docs
weight: 2523
url: /hi/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) फ़ंक्शन

Old obsolete casts. Will be removed in future versions.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य Exception प्रकार। |
| TFrom | स्रोत Exception प्रकार। |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const TFrom\& | स्रोत पॉइंटर। |

### वापसी मान

Cast result if cast is allowed or nullptr otherwise.

## टिप्पणी

Performs dynamic cast on Exception objects. Deprecated
:   पिछले संगतता के लिए रखा गया है। AsCast का उपयोग करें।

## System::DynamicCast_noerrno(SmartPtr\<TFrom\> const\&) फ़ंक्शन

Performs dynamic cast on [SmartPtr](../smartptr/) ऑब्जेक्ट्स।

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य संदर्भित प्रकार। |
| TFrom | स्रोत संदर्भित प्रकार। |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | स्रोत पॉइंटर। |

### वापसी मान

Cast result if cast is allowed or nullptr otherwise.

अप्रचलित
:   पिछले संगतता के लिए रखा गया है। AsCast का उपयोग करें।

## System::DynamicCast_noerrno(SmartPtr\<TFrom\>) फ़ंक्शन

Performs dynamic cast on Objects को Exception ऑब्जेक्ट्स पर।

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य Exception प्रकार। |
| TFrom | [Object](../object/) प्रकार। |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | स्रोत पॉइंटर। |

### वापसी मान

Cast result if cast is allowed or nullptr otherwise.

अप्रचलित
:   पिछले संगतता के लिए रखा गया है। AsCast का उपयोग करें।

## देखें भी

* क्लास [SmartPtr](../smartptr/)
* क्लास [Object](../object/)
* संरचना [IsExceptionWrapper](../isexceptionwrapper/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)