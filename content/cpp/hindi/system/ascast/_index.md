---
title: AsCast()
second_title: Aspose.Slides for C++ API संदर्भ
description: "'as' ऑपरेटर कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में कास्ट करता है। जब सरल कंस्ट्रक्टर-सम कास्ट की आवश्यकता होती है, तब उपयोग किया जाता है।"
type: docs
weight: 2640
url: /hi/system/ascast/
---
## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। जब सरल कंस्ट्रक्टर-सम समान कास्ट की आवश्यकता होती है, तो यह उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। जब स्रोत और परिणाम प्रकार समान होते हैं, तब यह उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। अपवाद रैपर के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। वस्तु को अपवाद में कास्ट करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। जब स्रोत और परिणाम दोनों स्मार्ट पॉइंटर होते हैं, तब यह उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। जब स्रोत और परिणाम दोनों स्मार्ट पॉइंटर होते हैं (परिणाम प्रकार में स्पष्ट SmartPtr<...> के साथ), तब यह उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम। यदि कोई रूपांतरण उपलब्ध नहीं है तो nullptr रिटर्न करता है।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। ऑब्जेक्ट को nullable में अनबॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम। यदि कोई रूपांतरण उपलब्ध नहीं है तो खाली nullable रिटर्न करता है।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। गैर-ऑब्जेक्ट प्रकार में अवैध अनबॉक्सिंग।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

हमेशा null रिटर्न करता है।

## System::AsCast(const Source\&) function

गैर-ऑब्जेक्ट प्रकार में अवैध अनबॉक्सिंग।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

हमेशा null रिटर्न करता है।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। nullable ऑब्जेक्ट को बॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। सामान्य ऑब्जेक्ट को बॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। सामान्य ऑब्जेक्ट को बॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। स्ट्रिंग को अनबॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। nullptr केसिंग के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::AsCast(const Source\&) function

स्रोत प्रकार को परिणाम प्रकार में 'as' ऑपरेटर कास्ट का उपयोग करके कास्ट करता है। एरेज़ के बीच कास्ट करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिए। |

### रिटर्न वैल्यू

कास्ट परिणाम। यदि किसी भी एरे सदस्य के लिए रूपांतरण उपलब्ध नहीं है तो nullptr रिटर्न करता है।

## देखें

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)