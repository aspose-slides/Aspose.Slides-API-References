---
title: StaticCast()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: SmartPtr ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।
type: docs
weight: 2562
url: /hi/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) function

[SmartPtr](../smartptr/) ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | लक्ष्य pointee प्रकार। |
| TFrom | स्रोत pointee प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | स्रोत पॉइंटर। |

### Return Value

यदि कास्ट की अनुमति है तो कास्ट परिणाम लौटाता है।

अप्रचलित
:   बैकवर्ड संगतता के लिए रखा गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::StaticCast(WeakPtr\<TFrom\> const\&) function

[WeakPtr](../weakptr/) ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | लक्ष्य pointee प्रकार। |
| TFrom | स्रोत pointee प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | स्रोत पॉइंटर। |

### Return Value

यदि कास्ट की अनुमति है तो कास्ट परिणाम लौटाता है।

अप्रचलित
:   बैकवर्ड संगतता के लिए रखा गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::StaticCast(std::nullptr_t) function

null ऑब्जेक्ट्स का स्थैतिक कास्ट करता है।

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | लक्ष्य pointee प्रकार। |

### Return Value

nullptr।

अप्रचलित
:   बैकवर्ड संगतता के लिए रखा गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::StaticCast(TFrom) function

अंकात्मक प्रकारों के लिए विशेषण।

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) function

[String](../string/) से [String](../string/) में कास्ट प्रक्रिया करता है।

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) function

अंकात्मक प्रकारों के लिए विशेषण।

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) function

गैर-पॉइंटर ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | लक्ष्य प्रकार। |
| TFrom | स्रोत प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | स्रोत ऑब्जेक्ट। |

### Return Value

यदि कास्ट की अनुमति है तो कास्ट परिणाम लौटाता है।

अप्रचलित
:   बैकवर्ड संगतता के लिए रखा गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::StaticCast(const TFrom\&) function

Exception ऑब्जेक्ट्स पर स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | लक्ष्य Exception प्रकार। |
| TFrom | स्रोत Exception प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | स्रोत पॉइंटर। |

### Return Value

यदि कास्ट की अनुमति है तो कास्ट परिणाम लौटाता है।

अप्रचलित
:   बैकवर्ड संगतता के लिए रखा गया है। इसके बजाय ExplicitCast का उपयोग करें।

## System::StaticCast(SmartPtr\<TFrom\>) function

ऑब्जेक्ट्स को Exception ऑब्जेक्ट्स में स्थैतिक कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | लक्ष्य Exception प्रकार। |
| TFrom | [Object](../object/) प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | स्रोत पॉइंटर। |

### Return Value

यदि कास्ट की अनुमति है तो कास्ट परिणाम लौटाता है।

अप्रचलित
:   बैकवर्ड संगतता के लिए रखा गया है। इसके बजाय ExplicitCast का उपयोग करें।

## See Also

* Class [SmartPtr](../smartptr/)
* Class [WeakPtr](../weakptr/)
* Class [String](../string/)
* Class [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [CastResult](../castresult/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)