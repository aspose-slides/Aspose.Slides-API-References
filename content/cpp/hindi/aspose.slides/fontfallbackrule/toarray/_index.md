---
title: ToArray()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है।
type: docs
weight: 144
url: /hi/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() method


इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है।

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```


### Return Value

Array of [System::String](../../../system/string/)
## Remarks



```cpp
// फ़ॉन्ट्स की सूची वाली एक नियम बनाएं।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// सभी फ़ॉन्ट नामों को ऐरे के रूप में प्राप्त करें।
ArrayPtr<String> fontNames = newRule->ToArray();
```


## FontFallBackRule::ToArray(int32_t, int32_t) method


सूची में निर्दिष्ट रेंज से सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है।

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| startIndex | **int32_t** | जोड़ने के लिए पहले फ़ॉन्ट का सूचकांक। |
| count | **int32_t** | जोड़ने के लिए फ़ॉन्टों की संख्या। |

### Return Value

Array of [System::String](../../../system/string/)
## Remarks



```cpp
// फ़ॉन्ट्स की सूची वाले एक नियम बनाएं।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// अंतिम दो फ़ॉन्ट नामों को ऐरे के रूप में प्राप्त करें।
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## See Also

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [FontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)