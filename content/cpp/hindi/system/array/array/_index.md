---
title: Array()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक खाली सरणी बनाता है।
type: docs
weight: 1
url: /hi/system/array/array/
---
## Array::Array() constructor

एक खाली सरणी बनाता है।

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) constructor

भरण कन्स्ट्रक्टर।

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| count | int | सरणी का प्रारंभिक आकार |
| init | const T\& | सरणी को भरने के लिए उपयोग किया गया प्रारंभिक मान |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructor

भरण कन्स्ट्रक्टर।

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| ValueType | प्रारंभिक मान का प्रकार |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | सरणी का प्रारंभिक आकार |
| init | [ValueType](../valuetype/) | सरणी को भरने के लिए उपयोग किया गया प्रारंभिक मान |

## Array::Array(int, const T) constructor

भरण कन्स्ट्रक्टर।

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| count | int | सरणी का प्रारंभिक आकार |
| inits | const T | सरणी को भरने के लिए मान |

## Array::Array(vector_t\&&) constructor

मूव कन्स्ट्रक्टर।

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, जिसके तत्व सरणी द्वारा प्राप्त किए जाते हैं |

## Array::Array(const vector_t\&) constructor

कॉपी कन्स्ट्रक्टर।

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector से मान कॉपी करने के लिए |

## Array::Array(const std::vector\<Q\>\&) constructor

एक [Array](../) वस्तु बनाता है और उसे उन मानों से भरता है जो std::vector वस्तु से कॉपी किए गए हैं, जिसका मान प्रकार **T** के समान है लेकिन **UnderlyingType** से भिन्न है।

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| Q | std::vector वस्तु के तत्वों का प्रकार, जिससे तत्वों को कॉपी किया जाता है |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector जिससे मानों को कॉपी किया जाता है |

## Array::Array(std::vector\<Q\>\&&) constructor

एक [Array](../) वस्तु बनाता है और उसे उन मानों से भरता है जो std::vector वस्तु से स्थानांतरित (move) किए गए हैं, जिसका मान प्रकार **T** के समान है लेकिन **UnderlyingType** से भिन्न है।

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| Q | std::vector वस्तु के तत्वों का प्रकार, जिससे तत्वों को स्थानांतरित किया जाता है |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector जिससे मानों को कॉपी किया जाता है |

## Array::Array(std::initializer_list\<UnderlyingType\>) constructor

एक [Array](../) वस्तु बनाता है और उसे निर्दिष्ट इनिशियलाइज़र सूची से मानों से भरता है, जिसमें **UnderlyingType** प्रकार के तत्व होते हैं।

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | इनिशियलाइज़र सूची जिसमें सरणी को भरने के लिए तत्व होते हैं |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructor

एक [Array](../) वस्तु बनाता है और उसे निर्दिष्ट array से मानों से भरता है, जिसमें **UnderlyingType** प्रकार के तत्व होते हैं।

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| InitArraySize | **init** array में तत्वों की संख्या। |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) जिसे निर्मित हो रही सरणी में कॉपी किया जाएगा। |

## Array::Array(std::initializer_list\<bool\>, int) constructor

एक [Array](../) वस्तु बनाता है और उसे निर्दिष्ट इनिशियलाइज़र सूची से मानों से भरता है, जिसमें bool प्रकार के तत्व होते हैं।

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | इनिशियलाइज़र सूची जिसमें सरणी को भरने के लिए तत्व होते हैं |

## See Also

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)