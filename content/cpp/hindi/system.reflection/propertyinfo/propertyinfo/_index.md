---
title: PropertyInfo()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: कंस्ट्रक्टर। केवल const getter वाला प्रॉपर्टी।
type: docs
weight: 66
url: /hi/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) कंस्ट्रक्टर

कंस्ट्रक्टर। केवल const getter वाला प्रॉपर्टी।

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) कंस्ट्रक्टर

कंस्ट्रक्टर। केवल non-const getter वाला प्रॉपर्टी।

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) कंस्ट्रक्टर

कंस्ट्रक्टर। [Nullable](../../../system/nullable/) प्रॉपर्टी जिसमें setter और getter है।

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) कंस्ट्रक्टर

कंस्ट्रक्टर। [Nullable](../../../system/nullable/) प्रॉपर्टी केवल const getter वाला।

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) कंस्ट्रक्टर

कंस्ट्रक्टर। [Object](../../../system/object/) प्रॉपर्टी केवल getter वाला।

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) कंस्ट्रक्टर

String प्रॉपर्टी जानकारी बनाता है।

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) कंस्ट्रक्टर

Class से const getter के साथ string प्रॉपर्टी जानकारी बनाता है।

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) कंस्ट्रक्टर

[Decimal](../../../system/decimal/) प्रॉपर्टी जानकारी बनाता है।

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) कंस्ट्रक्टर

Class से const getter के साथ [Decimal](../../../system/decimal/) प्रॉपर्टी जानकारी बनाता है।

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) कंस्ट्रक्टर

Boolean प्रॉपर्टी जानकारी बनाता है।

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) कंस्ट्रक्टर

Class से const getter के साथ Boolean प्रॉपर्टी जानकारी बनाता है।

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) कंस्ट्रक्टर

**int64_t** प्रॉपर्टी जानकारी बनाता है।

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) कंस्ट्रक्टर

**int64_t** प्रॉपर्टी जानकारी Class से const getter के साथ बनाता है।

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() const | Getter method. |

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [PropertyInfo](../)
* क्लास [Nullable](../../../system/nullable/)
* क्लास [Decimal](../../../system/decimal/)
* नेमस्पेस [System::Reflection](../../)
* लाइब्रेरी [Aspose.Slides](../../../)