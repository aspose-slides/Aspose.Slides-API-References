---
title: Is()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: 'is' घोषणा पैटर्न अनुवाद को लागू करता है।
type: docs
weight: 2302
url: /hi/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) function

Implements ‘is’ घोषणा पैटर्न अनुवाद को लागू करता है।

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| PatternT | जांचने के लिए प्रकार। |
| ExpressionT | बाएँ अभिव्यक्ति का प्रकार। |
| ResultT | परिणाम अभिव्यक्ति का प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | const ExpressionT\& | जाँच की जाने वाली अभिव्यक्ति। |
| result | ResultT\& | जाँच किए गए प्रकार को असाइन किया जाने वाला चर। |

### वापसी मान

true if type check is successful, false otherwise.

## System::Is(const ExpressionT\&, const ConstantT\&) function

Implements ‘is’ स्थायी पैटर्न अनुवाद को लागू करता है।

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ExpressionT | बाएँ अभिव्यक्ति का प्रकार। |
| ConstantT | स्थिर अभिव्यक्ति का प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | const ExpressionT\& | जाँच की जाने वाली अभिव्यक्ति। |
| constant | const ConstantT\& | बाएँ वाले के साथ तुलना की जाने वाली अभिव्यक्ति। |

### वापसी मान

true if type check is successful, false otherwise.

## System::Is(const E\&, const A\&) function

उच्च-स्तरीय मिलान फ़ंक्शन। एक मान पर पैटर्न लागू करता है।

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| A | पैटर्न प्रकार (Details::Pattern से विरासत में लेना आवश्यक है)। |
| E | मिलाने वाले मान का प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| e | const E\& | जिस मान से मिलान करना है। |
| a | const A\& | लागू करने वाला पैटर्न। |

### वापसी मान

true if the pattern matches the value.

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)