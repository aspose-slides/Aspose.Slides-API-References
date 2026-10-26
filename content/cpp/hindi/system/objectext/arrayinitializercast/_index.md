---
title: ArrayInitializerCast()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: ऐरे के मूलभूत मानों को परिवर्तित करता है (जिसे C# स्वतः करता है लेकिन C++ स्पष्ट रूप से नहीं करता)।
type: docs
weight: 209
url: /hi/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) विधि

ऐरे के मूलभूत मानों को परिवर्तित करता है (जिसे C# स्वतः करता है लेकिन C++ स्पष्ट रूप से नहीं करता)।

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| To | लक्ष्य प्रकार। |
| From | स्रोत प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | From ... | लक्ष्य ऐरे में परिवर्तित करने और धकेलने के मान। |

### रिटर्न वैल्यू

[Array](../../array/) सभी तर्कों की परिवर्तित प्रतियों को समान क्रम में रखता है।

## संबंधित देखें

* क्लास [ObjectExt](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)