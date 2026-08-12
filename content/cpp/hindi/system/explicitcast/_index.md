---
title: ExplicitCast()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। जब स्रोत और परिणाम प्रकार समान हों तो उपयोग किया जाता है।
type: docs
weight: 2627
url: /hi/system/explicitcast/
---
## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। जब स्रोत और परिणाम प्रकार समान हों तो उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। जब सरल कंस्ट्रक्टर-सम कास्ट आवश्यक हो तो उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। अपवाद रैपरों के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। ऑब्जेक्ट को अपवाद में कास्ट करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। जब स्रोत और परिणाम दोनों स्मार्ट पॉइंटर हों (परिणाम प्रकार में स्पष्ट SmartPtr<...> बिना) तब उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(Source) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। जब कच्चे पॉइंटर को स्मार्ट पॉइंटर में कास्ट किया जाता है तब उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | Source | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। जब स्रोत और परिणाम दोनों स्मार्ट पॉइंटर हों (परिणाम प्रकार में स्पष्ट SmartPtr<...> के साथ) तब उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। नल योग्य में ऑब्जेक्ट को अनबॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। नल योग्य को बॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। नल योग्य ऑब्जेक्ट को अनबॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। एनीम को बॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। हिप पर वैल्यू टाइप्स को कॉपी करने के लिए उपयोग किया जाता है जब वैल्यू टाइप को स्मार्ट पॉइंटर के रूप में संदर्भित किया जाना चाहिए (जेनरिक्स में इंटरफ़ेस टाइप से बाध्य लेकिन इस इंटरफ़ेस को लागू करने वाली स्ट्रक्चर से विशेषीकृत)।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। वैल्यू टाइप्स से इंटरफ़ेस प्राप्त करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। सामान्य बॉक्सिंग के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। [System::String](../string/) बॉक्सिंग के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। इंटरफ़ेस को अनबॉक्स करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। सामान्य अनबॉक्सिंग के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। nullptr कास्टिंग के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## System::ExplicitCast(const Source\&) फ़ंक्शन

स्पष्ट कास्ट का उपयोग करके स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। ऐरे के बीच कास्ट करने के लिए उपयोग किया जाता है।

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) को कास्ट करने के लिये। |

### रिटर्न वैल्यू

कास्ट परिणाम।

## See Also

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)