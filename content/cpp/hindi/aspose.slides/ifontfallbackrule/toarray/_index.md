---
title: ToArray()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस नियम के सभी FallBack फ़ॉन्ट्स वाला एक एरे बनाता है और वापस करता है।
type: docs
weight: 105
url: /hi/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() मेथड

इस नियम के लिए सभी FallBack फ़ॉन्ट्स वाला एक एरे बनाता है और वापस करता है।

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### Return Value

एरे [System::String](../../../system/string/)
## Remarks

```cpp
// एक नियम बनाता है जिसमें फ़ॉन्ट्स की सूची होती है.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// सभी फ़ॉन्ट-नामों को एरे के रूप में प्राप्त करें
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) मेथड

निर्दिष्ट रेंज में सूची से सभी FallBack फ़ॉन्ट्स वाला एक एरे बनाता है और वापस करता है।

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| startIndex | **int32_t** | पहले फ़ॉन्ट को जोड़ने का सूचकांक। |
| count | **int32_t** | जोड़ने के लिये फ़ॉन्ट्स की संख्या। |

### Return Value

एरे [System::String](../../../system/string/)
## Remarks

```cpp
// एक नियम बनाता है जिसमें फ़ॉन्ट्स की सूची होती है.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// अंतिम दो फ़ॉन्ट-नामों को एरे के रूप में प्राप्त करें
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [IFontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)