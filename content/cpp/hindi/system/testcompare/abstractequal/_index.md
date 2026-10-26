---
title: AbstractEqual()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: अज्ञात प्रकार की दो कलेक्शन की तुलना करता है।
type: docs
weight: 14
url: /hi/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) method

अज्ञात प्रकार की दो कलेक्शन की तुलना करता है।

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | कलेक्शन तत्व प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | बाएँ हाथ का संग्रह। |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | दाएँ हाथ का संग्रह। |

### रिटर्न मान

यदि कलेक्शन मेल खाती हैं (उदाहरण के लिए दोनों null हैं), या यदि आकार मिलते हैं और तत्व मिलते हैं, तो true; अन्यथा false।

## संबंधित देखें

* क्लास [ICollection](../../../system.collections.generic/icollection/)
* स्ट्रक्ट [TestCompare](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)