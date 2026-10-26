---
title: Enum
second_title: Aspose.Slides for C++ API संदर्भ
description: enum प्रकार के मानों पर कुछ संचालन करने वाले मेथड्स प्रदान करता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवा नहीं है। आपको किसी भी माध्यम से इसके इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 1587
url: /hi/system/enum/
---
## एनम संरचना

कुछ ऑपरेशनों को enum प्रकार के मानों पर लागू करने वाले मेथड्स प्रदान करता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवा नहीं है। आपको किसी भी माध्यम से इसके इंस्टेंस नहीं बनाना चाहिए।

```cpp
template<class E,class Guard>class Enum
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| E | जिस enum प्रकार के मानों को क्लास संभालती है |
| Guard | सेवा प्रकार तर्क जिसका उद्देश्य यह सुनिश्चित करना है कि **E** एक enumeration प्रकार है |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| static int [Compare](./compare/)(E, T) | निर्दिष्ट enumeration स्थिरांकों के मानों की अंकगणितीय तुलना करता है। |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | निर्दिष्ट मान के साथ enumeration स्थिरांक का नाम लौटाता है। |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | निर्दिष्ट मान के साथ enumeration स्थिरांक का नाम लौटाता है। |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | enumeration **E** के सभी सदस्यों के नामों वाला एक array लौटाता है। |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | enumeration का मूलभूत प्रकार लौटाता है। |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | enumeration **E** के सभी सदस्यों वाला एक array लौटाता है। |
| static **bool** [HasFlag](./hasflag/)(E, E) | निर्दिष्ट enum मान के बाइनरी प्रतिनिधित्व में निर्दिष्ट बिट्स सेट हैं या नहीं निर्धारित करता है। |
| static **bool** [IsDefined](./isdefined/)(E) | निर्धारित करता है कि क्या निर्दिष्ट मान enumeration प्रकार **E** का सदस्य है। |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | निर्धारित करता है कि क्या निर्दिष्ट मान enumeration प्रकार **T** का सदस्य है। |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | निर्धारित करता है कि क्या निर्दिष्ट नाम वाला मान enum **E** के सदस्यों में है। |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | निर्दिष्ट स्ट्रिंग को समकक्ष enum स्थिरांक में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | निर्दिष्ट स्ट्रिंग को समकक्ष enum स्थिरांक में बदलने का प्रयास करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | निर्दिष्ट स्ट्रिंग को समकक्ष enum स्थिरांक में बदलने का प्रयास करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | enum के मूलभूत प्रकार का उपनाम। |

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)